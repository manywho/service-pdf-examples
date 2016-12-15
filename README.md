ManyWho PDF Service Examples
============================

These flows are examples of how to use PDF Service with ManyWho.

## Usage

**Example: Create PDF from URL**

Import the flow (example-create-pdf-from-url.json) into your ManyWho account.
Run the flow and upload a file (e.g. example_populate_pdf.pdf) then click in "go".
Click in the link and you will see a pdf.

**Example: Populate PDF**

Import the flow (example-populate-pdf.json) into your ManyWho account.
Download the file example_populate_pdf.pdf, open it and check that is not populated.
Run the flow and upload the file example_populate_pdf.pdf, the flow will show you a link, open that link in the browser.
You should be able to see the pdf populated.

**Example: Generate PDF from HTML**

Import the flow (example-generate-pdf-from-html.json) into your ManyWho account.
Run the flow, you will see a link, open that link in the browser.
You should be able to see the pdf with the word "content".

**Example: Concatenate PDF**

Import the flow (example-concatenate-pdf.json) into your ManyWho account.
Run the flow, upload a file and click next, upload another file and click next.
Click in the link that appear in the screen, you should be able to see the pdf result of concatenate the uploaded pdfs.

**Example: PDF Type**

Import the flow (example-pdf-type.json) into your ManyWho account.
Run the flow, You will see a list of PDF Input Fields.
Note: if you send as parameter this list and the example_populate_pdf.pdf to the action Populate Pdf forms you will get as result the pdf populated.

### More info

You can have more information of how to configure this service follow the instructions in https://github.com/manywho/service-box/wiki
If you need to deploy the service in your oun environment you can find the code in https://github.com/manywho/service-box

## Contributing

Contribution are welcome to the project - whether they are feature requests, improvements or bug fixes! Refer to 
[CONTRIBUTING.md](CONTRIBUTING.md) for our contribution requirements.

## License

This service is released under the [MIT License](http://opensource.org/licenses/mit-license.php).
