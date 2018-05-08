# angular-dropzone
AngularJS directive for Dropzone.js

NOTE: THIS IS A COPY OF, WHAT I BELIEVE WAS AVAILABLE AT URL: https://github.com/yerlikayao/angular-dropzone4.git AND FOR SOME REASON CEASED TO EXIST. I HAVE JUST RESTORED IT FROM LOCAL FILE COPY AND PUT INTO THIS REPO SO I CAN DIRECT Bower TO USE IT.


## Installation
```
bower install angular-dropzone
```

## Usage

### html

```
<form class="dropzone" method="post" enctype="multipart/form-data" ng-dropzone dropzone="dropzone" dropzone-config="dropzoneConfig">
  <input name="file" type="file" multiple />
</form>
```

### js
```
$scope.dropzoneConfig = {
  parallelUploads: 3,
  maxFileSize: 30
};
```
