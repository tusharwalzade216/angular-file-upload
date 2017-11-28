# angular-file-upload
modifications in https://github.com/nervgh/angular-file-upload for uploading multiple files in a single request

- changes in angular-file-upload.js
  - added a new function UploadAllAtOnce() which is to be used instead of UploadAll() in further processing in resp. controller/HTML
  - Updated a function onCompleteAll(), for immediate response.
