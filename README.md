## Import transaction template
Most trading platforms provide an export function of transactions. The result of this export can possibly be imported into GT. Since each trading platform implements its own design of **documents**, an import template must be created in GT according to each of these documents. GT can handle two document types **PDF** and **CSV**.

### Import implementation
In most cases, the import function generally implemented in GT with the corresponding import templates is sufficient to process the documents of a trading platform. In all other cases, an import function must be implemented in GT.

### Template group
For a trading platform there can be one or more templates, therefore they are kept in a **Template Group**. The key of a single **Import Template** is formed from the following four properties and must be unique per template group. This key is used when importing an import template to decide whether it is a new template or whether it overwrites an existing template.
