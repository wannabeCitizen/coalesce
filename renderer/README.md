This directory contains the code necessary to convert articles into their
relevant set of JSON metadata.  The `./render` script will be in charge of
using all necessary tools for rendering the articles.  Any tools created to
help this process should be in their own directory and should have very specific
uses.  In addition, their inputs should only be a relative path to the file or
directory that script needs to process.
