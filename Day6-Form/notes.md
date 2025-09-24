# Form in HTML:-
1. Forms are used to accept input from the user.
2. To create form in html, we use form tag.
3. To create input field we use input tag. It is unpair tag.
   <input type="text">
4. Input tag we have to write with in form tag.

# Attributes in input tag:-
1. type:- type attribute is used to specify which type of data we can accept in that input field.

1. text
2. tel
3. email
4. password
5. file mutliple attribute
6. date
7. time
8. datetime-local
9. search
10. url
11. range
12. color
13. number
14. radio
15. checkbox
16. hidden

2. name:- name attribute is used to provide name to the input field.

3. value:- value attribute is used to provide initial (starting) value to the input field.

4. disabled:- Input field is disabled. User can not access the input field.

5. readonly:- It will make the input field as readonly. user can access the input field but can not change or edit the value.

6. required:- It will make the input field as required or mandatory to be filled. If input field is empty form will not be submitted.

7. placeholder:- It is used to provide hint to the user.

8. autofocus:- It will automatically focus an input field after page reload or page open.

9. autocomplete:- It is used to provide suggestions to the user.
   on, off

10. maxlength:- 10

11. minlength:- 2

# Input Tag:- 
1. Input tag is single line input field.
2. It is unpair tag.

# Textarea:- 
1. It is used to create multi line input field.
2. It is pair tag.

cols attribute:- width of text area
rows attribute:- height of text area

# Label Tag:-
1. Label tag is used to connect text with the input field.
2. The text we want to connect we have to write within label tag.
3. To connect text with the input field we have to use id attribute inside input tag.
4. That id's value we have to pass to the label tag for attribute.
5. whenever user click on that text if will focus the respective input field.

# Fieldset tag:-
1. Fieldset tag is used to group form control and it is used to create one box around the form elements.
2. Fieldset tag we have to write within form tag.

# Legend Tag:-
1. Legend tag is used to provide title or caption to the fieldset tag.
2. Legend tag we have to write within fieldset tag.

# Select tag:- Select List/ Dropdown List
1. Select Tag is used to create select list or dropdown list.
2. To create select list we use select tag.
3. To create options we use option tag.
4. Option tag we have to write within select tag.

<select name="" id="">
        <option value=""></option>
        <option value=""></option>
        <option value=""></option>
        <option value=""></option>
</select>


# Datalist/ Suggestion List/ Autocomplete List:-

# Datalist tag:- Id attribute
# Input Tag:- list attribute

1. The Datalist Tag is introduced in Html-5.
2. The Html datalist tag is used to provide an autocomplete feature on the form element.
3. Datalist tag is a container tag.
4. It is block level element.
5. It is used to provide a list of predefined options to the users.
6. Datalist tag is used to create suggestion list or autocomplete list.
7. The <datalist> tag contains a set of <option> tags that define the options in the list.
8. We are binding the suggestion list with the input field, for this we have to provide 'list' attribute in the input tag and 'id' attribute in the datalist tag, this same 'id' we have to provide in the 'list' attribute of input tag.
9. Whenever the user inputs in the input field related suggestions are displayed.

10. The advantage of using the datalist tag is that it allows users to enter values that are not present in the options list.

