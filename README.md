# formFilter

A lightweight **JavaScript form validation helper** built on top of **jQuery Validate**.  

It allows you to:

- Skip required validation for specific fields  
- Add **custom pattern rules**  
- Add **minimum/maximum length validation**  
- Add **custom messages** (single or multiple)  
- Support **multiple fields at once**  
- Fully configurable, easy to maintain and scale  

---

## Table of Contents

1. [Installation](#installation)  
2. [Initialization](#initialization)  
3. [Methods](#methods)  
    - [is_required](#is_required)  
    - [addPattern](#addpattern)  
    - [addMinLength](#addminlength)  
    - [addMaxLength](#addmaxlength)  
    - [addMessage](#addmessage)  
    - [init](#init)  
    - [destroy](#destroy)  
4. [Example Workflow](#example-workflow)  
5. [Notes](#notes)  

---

## Installation

Include jQuery and jQuery Validate first:

```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="https://cdn.jsdelivr.net/jquery.validation/1.19.5/jquery.validate.min.js"></script>
<script type="module" src="path/to/formFilter.js"></script>
