Properties are pieces of metadata associated with a particular custom type.
A custom type can have one or multiple properties.
You can create a new property by **double clicking** the custom type for which you want to add the property.
**Note that properties within a custom type must have unique names.**

1. In the custom types view, click the custom type for which you would like to add a property.
The relevant property page will appear.
This page enables you to create properties and to view a list of the existing properties for the custom type.

![/en/attachments/9.png](/en/attachments/9.png)
 
2. To create a new property, click on the Create Property button.
The Create Property window will appear afterward.

![/en/attachments/10.png](/en/attachments/10.png)

3. Enter the details for the new property. Fields marked with an asterisk (*) are required.

![/en/attachments/11.png](/en/attachments/11.png)

- Enter a name for the property.
Only alphanumeric characters, hyphens (-) and underscores (_) are allowed. The property name will automatically prefix the model namespace.

- Select an optional display label for the property.
The display label is shown as the property name to the end users in Alfresco Share.

- Enter an optional description of the property.
- Select the data type this property can contain.

![/en/attachments/12.png](/en/attachments/12.png)

Data types describe the fundamental types of data the repository will use to store properties. The available out-of-the-box data types are:

![/en/attachments/13.png](/en/attachments/13.png)

4. Select if the property value is optional or mandatory, and if this is enforced by the system.
The available options are:
- Optional:
Specifies that the property value is not required and the property can be left blank.
- Mandatory:
Specifies that the property value is required and must be filled. The property will be marked with an asterisk afterward.
5. Select if the property should be multi-valued.

6. Specify an optional default value for the property created.
 **The default value should be appropriate for the selected data type. For example, if the data type is d:int, the default value must be an integer.**
The control/layout of Default Value depends on the selected data type. For example, if you select d:text as the data type, then the Default Value layout is a text box, where as if you select d:int as the data type, then the Default Value layout is a spin control.

7. Select the optional constraint for the property.
Some additional fields will be displayed depending on what constraint option you select.

![/en/attachments/14.png](/en/attachments/14.png)

- Regular Exprssion:
Specify a regular expression for the constraint. This field is mandatory.
- Minimum / Maximum length:
Minimum Length specifies the minimum length allowed for the property.
Maximum Length specifies the maximum length allowed for the property.
Both the fields are mandatory.
- Minimum / maximum value:
Minimum Value specifies the minimum value allowed for the property.
Maximum Value specifies the maximum value allowed for the property.
Both the fields are mandatory.
- List of Values:
Enables the user to enter the list of allowed values, with each new item on a new line. This field is mandatory.
- Java class: 
Class name enables you to enter the fully qualified name of the class to use as a constraint.

8. To enable the property to be used for searching, select the appropriate searching option from the Indexing drop-down list.

![/en/attachments/15.png](/en/attachments/15.png)

9. To create a new property, click **Create**. To create another property, click Create Property and Start Another or click Cancel if you do not want to save the changes.
The property created appears in the Property List view.

![/en/attachments/16.png](/en/attachments/16.png)