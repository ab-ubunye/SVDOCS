The Model Editor in DocVolante allows you to create and manage your own custom models. This is a user-friendly tool that enables you to add custom types, aspects and properties to your models.

**What is a model?**

A model is a fundamental building block of the content repository that provides a foundation for structuring content and working with content. A model has the following characteristics:
- It describes the data being stored.
- It allows the management of content metadata by applying custom types or aspects to the content and folders.
- It is uniquely identified by its defined Namespace, Prefix, and Name.
- It is defined using a small set of building blocks: custom types, aspects, properties, and constraints.

**Custom types**

A custom type enumerates the properties and relationships that a file of that type can support. Typically, types represents nodes with support for properties and the ability to inherit the definition of a parent type. Content and Folder are the two important types defined out-of-the-box.

**Aspects**

An aspect is a collection of properties that can encapsulate both data and behaviour, providing a flexible tool for modeling content. Aspects add extra functionality and properties to the models by attaching them to custom types. A file must be of a single type, but may have one or more aspects attached to it. By default, the content repository comprises of some out-of-the-box aspects, such as Classifiable, Versionable, and so on.

**Please note that the current version of the Model Editor does not support the creation of aspects.**

**Properties**

Properties are metadata which describes the content. For example, Author is a property which specifies the person who wrote the content.

**Constraints**

Constraints control the input property values. For example, you can specify that the author name must not be more than 40 characters.
