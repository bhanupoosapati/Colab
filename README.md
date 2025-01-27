# Service account credentials
- Follow: https://developers.google.com/workspace/guides/create-credentials
- Get credential.json (project-name-****.json) file.
- enable Docs and Drive APIs from https://console.cloud.google.com/apis/library for your project.

# Open colab
- Go To: https://colab.research.google.com/
- Signin and create new notebook in drive.
* Left side drawer click files -> 
  * Upload credential.json from above step 
  * Upload input.md file (content that needs to be parsed to docs)

## Authenticate
## Create Doc in drive: create_google_doc(creds)
## Make doc public so that can be viewed in browser: make_document_public
## open in new tab: https://docs.google.com/document/d/{docuemnt_id} 
## parse and edit and view result.
## time.sleep() to not exceed per min quota.