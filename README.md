# vcf-hosting

This project hosts my Virtual Contact File or vCard (.vcf) files online using GitHub Pages. The purpose is to provide a simple URL that can be written to an NFC tag, allowing anyone who scans the tag to easily download and add, for example, contact information to their device.

## Purpose

- **Share Contact Information Easily**: By scanning an NFC tag, people can quickly access contact details.
- **Update Contact Information Remotely**: The URL can be updated with new VCF files without physically needing to reprogram the NFC tag.
- **Free Hosting**: Utilizes GitHub Pages to host the VCF files for free.

## Usage

- **Hosted VCF URL**: The VCF file is available at `https://semplaatsman.github.io/vcf-hosting/contact.vcf`.
- **NFC Integration**: The URL can be programmed into an NFC tag. When the tag is scanned, it will direct the user to download a vfc file.

## Example VCF

Here’s an example of the VCF content hosted in this repository:

```plaintext
BEGIN:VCARD
VERSION:3.0
N:Doe;John;;Mr.;
FN:John Doe
ORG:Example Company
TITLE:Software Engineer
TEL;TYPE=WORK,VOICE:+1234567890
EMAIL:john.doe@example.com
URL:https://www.example.com
END:VCARD
