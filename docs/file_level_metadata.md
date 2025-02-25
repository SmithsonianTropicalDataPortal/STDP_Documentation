# File Level Metadata Guidelines

These are generally best practices and the user should take care to implement these as much as is applicable to their datasets. 

## Metadata that help to describe the data files 
### Within the portal user intereface

The portal will prompt you to describe your variates. 

For each column of each table, please provide:

* the attribute name (as used on the table)
* attribute label  (a descriptive display name, e.g. Temp_p2 = Temperature, probe 2)
* an attribute definition (unformatted text)
* a missing value indicator
* a category type
* units of measurement, if applicable 

(insert a figure series where it displays the user interface)

### As a set of descriptive documents

Alternatively, you can attach additional documentation that helps to describe your data. This can include a **README** document, **Data Dictionary**, and some sort of **Categorical Codebook**, if applicable. 

Functionally, this will capture the same information that would have otherwsie been noted in the portal interface but is now added as a user friendly set of descriptive files.  It is useful to create a data dictionary to describe your tabular data and accompany deposit in a repository so that others can interpret and reuse your data.

#### What is a Data Dictionary?

<div style="padding-left: 20px; border: 1px solid #ccc; background-color: #f9f9f9; padding: 10px; border-radius: 5px;">
    <strong>Definition:</strong> A document that outlines the structure, content, and variable definitions for a dataset or collection of data.
</div>

Open Science Framework provides a nice resource to learn more <a href="https://help.osf.io/article/217-how-to-make-a-data-dictionary" target="_blank">How to Make a Data Dictionary</a>

#### What is a Categorical Codebook?

<div style="padding-left: 20px; border: 1px solid #ccc; background-color: #f9f9f9; padding: 10px; border-radius: 5px;">
    <strong>Definition:</strong>  A document or table that provides definitions and explanations for categorical variables used in a dataset. It helps users understand the meaning of coded values (such as abbreviations, numeric codes, or labels) assigned to categorical data.
</div>

At the least, a categorical codebook should include:

* 