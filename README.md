# Invoices_automation
A free ``invoice automation`` from scratch with **Airtable**, **Google docs** and **Make**.

This a project for a self-employed occupational therapist who wasted a lot of time billing.

From a database on Airtable in which the data of each customer as well as the services invoiced were added, I was able to generate an invoice document from a Google doc template thanks to Make and create a draft email with the invoice attached in PDF format.

## Here is the workflow with Make:

- 1 - We check a new record in Airtable.

- 2 - We create an invoice in Google doc thanks to a template with variables in {{}}.

- 3 - We create a PDF file from the Google doc invoice just added.

- 4 - Last, we create a draft email with the PDF attached, the recipient email address and a body text previously added in Make and that's all!

![make](https://user-images.githubusercontent.com/18213190/230608152-958f4e0a-12d7-460e-9430-1f4ef5bedb4e.png)

