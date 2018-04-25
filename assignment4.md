# Tell me something interesting

Unlike previous US Presidents, Trump did not divest from his businesses before assuming office. Ethics organizations have as a consequence raised questions about how he may be benefiting financially from his presidency. We can't track all payments to his businesses, but due to campaign finance reporting requirements, we can track ones made by candidates or PACS. [Here](https://github.com/rshorey/digitalframeworks-spring18/blob/master/trump_expenditures.csv) is a csv of expenditures from entities tracked by the FEC to entities that came up when I searched for the word "Trump". Please note that this is raw, real-world data that has not been cleaned up (well, not much). You should inspect the data carefully and clean it up if necessary.

Find something interesting in this data, and write 300 words about it.

Please load the data in a google sheet and do your calculations there. Link the sheet at the bottom of your story.


Here's a data dictionary for the csv file:

* __committee_id__: the FEC-assigned ID for the political committee that made the payment
* __committee_name__: the name of the committee that made the payment
* __recipient_name__: the name of the recipient of the payment, as entered by the committee and not cleaned up by anyone
* __recipient_state__: the state where the recipient is located
* __disbursement_description__: the description of the payment, as entered by the committee and not cleaned up by anyone
* __disbursement_date__: the date of the payment
* __fec_election_type_desc__: was the electino affiliated with the payment a primary, general, special or runoff
* __fec_election_year__: in what year was the election affiliated with the payment?
* __payee_last_name__: last name of the recipient if it was a person
* __payee_first_name__: first name of the recipient if it was a person
* __payee_middle_name__: middle name of the recipient if it was a person
* __recipient_city__: the city where the recipient is located
* __recipient_zip__: the zipcode of the recipient
* __disbursement_purpose_category__: category of the payment, selected from a standardized list
* __memo_text__: additional information about the payment
* __pdf_url__: link to the page in the actual filing where the payment can be found
