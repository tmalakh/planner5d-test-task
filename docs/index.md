# Planner 5d Website Enhancement

## Get In Touch Form
It is required to build a contact form using UI Bootstrap v6 framework. The form should be placed on the [Business page](https://planner5d.com/business) above the footer. The design and the texts (in English) are provided in the [Figma file]().

The form includes input fields, Google reCaptcha and a Submit button.

The details of the input fields are given in the table below:
|Placeholder|Field Type|Required|Validation|
|------------------------|----------|--------|----------|
|Your name* |text|yes|- the field is not blank|
|Your contact email* |email|yes|- the field is not blank <br> - email address is valid|
|Phone number (optional) |tel|no||
|What type of industry you are in?* |text|yes|- the field is not blank|
|Your message * |text|yes|- the field is not blank|


## Placeholder

By default, the placeholder is located inside the field. When the user clicks the field, the placeholder moves to the top of the field. If the user types anything in the field, the placeholder remains at the top of the field. If the field remains blank, and the user clicks outside the field, the placeholder returns to its initial place inside the field.

## Validation

The validation of the input data occurs when the user clicks **Submit**. If the validation fails, a prompt is displayed near the corresponding field:

- if a field is blank, the prompt asks the user to fill in the field;
- if an invalid email is entered, the prompt asks to enter a valid email.

## Sending data

The data is sent to [https://planner5d.com/ru/business](https://planner5d.com/ru/business) in a POST request. 

Depending on the received response, a specific message is displayed on the page:
|Response|Message|
|--------|-------|
|200 OK |Your message has been sent successfully. We will contact you shortly.|
|Any other response |Failed to send your request. Please try again.|

## Translation

The translation into other supported languages will be provided later.

# Virtual Reality Section

The **Virtual Reality** section is a new section on the [Business page](https://planner5d.com/business). It is located under the **Augmented Reality** section.

The new element inherits the properties of the `<s-augmented-reality>` section above it. The main difference is the elements location and contents. 

Important features:

- Adaptive design: when the width of the **Virtual Reality** section is 711px or less, the right text block moves under the main image;
- The text block is aligned vertically to the main image.

The section layout is on the image below:

<img src="./Virtual Reality Mockup.jpg">

## Contents

**Header:** Virtual Reality

**Main image:** 
- [1044x1020](https://planner5d.com/s/6/images/business/vr/vr2@2x.jpg) 
- [522x510](https://planner5d.com/s/6/images/business/vr/vr2.jpg)

**List elements:**
|Item #|Icon|Text|
|------|----|----|
|1|[VR_icon_1](https://planner5d.com/s/6/images/business/vr/vr_icon_01.svg)|Create virtual reality experience where customers can explore your products.|
|2|[VR_icon_2](https://planner5d.com/s/6/images/business/vr/vr_icon_02.svg)|Allow users to alter textures and colors in real time as they immerse themselves in the design.|
|3|[VR_icon_3](https://planner5d.com/s/6/images/business/vr/vr_icon_03.svg)|Provide the option to edit items with one click and experience your products in 360 degrees.|

## Translation

The translation into other supported languages will be provided later.
