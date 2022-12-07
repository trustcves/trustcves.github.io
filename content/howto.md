# When to disclose?
Vulnerabilities should only made public if:
* The vendor was informed about the existence of the vulnerability
* The vendor agreed to disclosure OR the vendor did not agree but fixed the vulnerability regardless
* The vulnerability was reported to a CNA
* The CNA checked the details and provided a CVE number

# How to disclose?
Assuming that all points above are fulfilled the disclosure process can be done using this page. There is a markdown template available for the disclosure process. The template for publishing can be [found here](/template/publishTemplate.md). Read the comments in the markdown file and fill it.

Once the template has been filled out you can host your own **public** GitHub repository with the vulnerability, but it's advised to provide all of the information to me.

**Repository Structure**

* Root of the repository
  * Markdown.md
  * images
    * image1.png

The CI to automatically converts this to HTML and presents it on the page. All CVEs referenced using submodules. When using this structure, your *markdown.md* will not render images correctly in the preview, but it will be displayed correctly on the page.

