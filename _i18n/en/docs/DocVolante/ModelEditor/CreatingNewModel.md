You can create new models using the Model Editor page.

Please note that the current version of the model editor does not support the creation of models yet. But you can modify an existing model by editing it's content through custom types and properties.
Have a look at the custom type and property section for more details.


1. Click on the **Model Editor** link located in the side navigation bar.

![/en/attachments/1.png](/en/attachments/1.png)

2. By Clicking the **Create Model** button a window will appear that will enable you to fill in the details for the new model.
**Please note that the fields marked with an asterisk (*) are required.**

![/en/attachments/2.png](/en/attachments/2.png)![/en/attachments/3.png](/en/attachments/3.png)

- Enter the model namespace.
Namespaces provide a way to specify globally unique names for definitions within content models. All custom types, aspects, and properties have names which are made unique across the repository by using a namespace specific to the model. Using namespaces prevents name collisions when the models are shared across repositories. A namespace is composed of a URI and a prefix.
Only alphanumeric characters or a URI, for example, http://www.mycompany.com/model/mynamespace/1.0, are allowed.
**Do not use spaces or special characters and the namespace value must be unique within the repository.**

- Enter a short prefix for the model.
A prefix is just an abbreviation for the namespace identifier (URI), which is typically quite long. For example, if the namespace URI is http://example.org/contentmodels and associated prefix is ex, then the name **ex:customtype** means that customtype is a name defined within the namespace http://example.org/contentmodels.
Only alphanumeric characters, hyphens (-), and underscores (_) are allowed. Do not use spaces.
**The prefix value must be unique within the repository.**

- Enter a name for the model.
For example, Finance.
Only alphanumeric characters, hyphens (-), and underscores (_) are allowed. Do not use spaces or special characters.

- Specify an optional author for the model.
If you leave this field blank, it will be auto-filled, it is based on the current signed in user.

- Enter an optional description for the model.

- Click Create.

The new model will appear in the Models List view on the Model Editor page.
Additional information in the Models List view include the model ID and the model Status.

![/en/attachments/4.png](/en/attachments/4.png)

