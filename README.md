# jenkinsci-unstashParam-library

Code:
```sh
library 'jenkinsci-unstashParam-library'
node {
   def file_in_workspace = unstashParam "file"
   echo "cat ${file_in_workspace}"
}
```

