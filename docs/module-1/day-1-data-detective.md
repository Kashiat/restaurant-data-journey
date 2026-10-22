# Module 1 Day 1: Data Detective

## Exercise purpose

The purpose of this exercise was to classify different examples of data by data type, structure and likely format or medium.

## My completed classification

| Data example | Classification | Structure | Likely format / medium |
|---|---|---|---|
| Restaurant transaction table | Mixed: contains quantitative measures (price, quantity), qualitative categories (menu item) and identifiers (order ID) | Structured | CSV or database table |
| Customer review written online | Qualitative | Unstructured | Free text on a website, stored in a database or exported as text/JSON |
| JSON order response from a delivery application | Mixed: can hold quantitative, qualitative and identifier fields | Semi-structured | JSON |
| Menu price | Quantitative (a measurable value) | Structured (usually sits inside a table) | Field in a CSV or database table |
| Photograph of a meal | Qualitative | Unstructured | Image file, e.g. JPEG or PNG |
| Restaurant branch name | Qualitative (category), can also act as an identifier-like label | Structured | Field in a CSV or database table |
| Number of orders each day | Quantitative (a count) | Structured | CSV or database table |
| Spreadsheet containing employee shifts | Mixed: qualitative (staff names, roles), quantitative (hours) and dates | Structured | CSV |
| Audio recording of a customer-support call | Qualitative | Unstructured | Audio file, e.g. WAV or MP3 |
| Payment method | Qualitative (category, e.g. card or cash) | Structured | Field in transaction data (CSV or database table) |

**Key reminder:** a value made of digits is not automatically quantitative. An order ID labels a record rather than measuring anything. Structure is how data is organised; format is how data is stored or exchanged.


## What I learned

Classifying each example showed me that the same restaurant produces many different kinds of data, from numbers like menu prices and daily order counts
to words, images and audio like reviews, meal photos and support calls. I learned to look at each example in three separate ways: what type of data it is
(quantitative, qualitative or identifier), how it is organised (structured, semi-structured or unstructured) and how it is likely stored (such as CSV,
JSON, JPEG or MP3). The most useful lesson was that structure and format are not the same thing, and that a value containing digits is not automatically
quantitative; an order ID, for example, labels a record rather than measuring anything. I also noticed that some examples, like a transaction table or a
JSON order, hold a mix of data types at once, which made me realise real data is rarely just one thing.
