# Building Blocks

This is a project which aims to provide people who are technologically illiterate with easy to understand guides on how to do common tasks which are required in a world which increasingly uses technology.

This repo contains a database of instructions. Each file is a markdown file of instructions which follows a standard for metadata.

This repo by itself would likely be difficult to use by someone who needs help from these instrcutions, it's desgined to be used by a client (IE, a website which is dedicated towards helping people using technology) or to provide a standard set of instructions which can easily be referenced and sent to/printed for someone who needs access to them by someone who is well versed in technology.

## Metadata

Each file is structured is the format 

    # Title
    ## Subtitle (optional)
    ### software title, version, operating system
    1. Step one
    2. Step 2
       - Image/video (Optional, but encouraged) 
    3. Step 3
	  A. If you want to do option A, do this
	  B. If you want to do option B, do this
    4. Step 4

    #### Outside Resources
    - [Company support page](https://example.com)

Other features such as recommending a instruction sheets, recommending other relate sheets, and a search function for the database will be handled by the client which reads this database. 

## Database Structure

The database is sorted by owning company > software > version > action, for example, Microsoft Word would be stored as

- Microsoft
    - Word
      - Windows 1.14.1
        - Creating a new document
        - Opening an existing document
      - Windows 1.14.2
        - Creating a new document
        - Opening an existing document
    - Powerpoint
      - Creating a new presentation
      - Inserting an image
  

