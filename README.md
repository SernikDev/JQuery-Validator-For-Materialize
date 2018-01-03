# JQuery Validator For Materialize

** Remember that that validation comes just for improve better UX, so you will also need to make validation for your server sides script **

Very simple validator for data in html forms.
It's working good with Materialize library.

1. For now its only working with ```<input>``` and ```<textarea>``` fields.
2. Data can be send via Ajax Request if all fields are filled corectly.

## Every field should contain this attribute

1. Add to every ```<input>``` or ```<textarea>``` field attribute with value ```<data-required="required">```.

## Additional Email Validation

1. Add to ```<input>``` field attribute with value ```<data-type="email">```.