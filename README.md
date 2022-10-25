# SEC-Filings-API
<a href="https://https://tradefeeds.com/sec-filings-api/" rel="nofollow">Tradefeeds SEC Filings API Database</a> contains more than 19 million SEC filngs of 20 000+ publicly traded companies listed on the NYSE, NASDAQ and other stock exchanges. The API database contains all 200+ types of SEC filings. Companies’ filings submitted to the EDGAR system are financial statements and reports that receive a particular form name and form description by the U.S. Security and Exchange Commission. SEC filings are arranged around six key groupings: annual fillings (Form 10-K), quarterly filings (Form 10-Q), current reports (8-K), proxy filings (DEF14A), registration statements (Form 424B2), Section 16 filings (Form4) and slightly more. Tradefeeds customers predominantly look for API for these six groupings of SEC filings. However, they are also interested in other common types of SEC filings such as: Form 6-K, Forms 3 and 5, Form S-1, Form S-3, Form S-8 , Form 20-F, Form 40-F , Schedule 13, Form 144.  SEC filings data of different companies are searchable by stock ticker symbols and form types in the API URL Path field. The SEC Filings API database is set up in such a way that companies’ filings are arranged according to their company names, stock ticker symbols, ISIN and CIK numbers.

The data on SEC filings is available through JSON REST API or retrieved in downloadable excel or csv files. Tradefeeds SEC filings API database is suitable for use any type customers - from developers who build their applications for a specific audience to in-house teams in all-sized companies. You can find accurate and regulartly updated data on SEC filings. Our team updated the API database each quarter.

Tradefeeds subscription packages are developed in such a way to serve all customers' needs. For the moment, there is no free trial provided. In case that you are a researcher or a student, we could negotiate a free trial. <a href="https://tradefeeds.com/pricing-subscription-plans/" rel="nofollow">Sign up for an API key</a> and we work out your case.




<h2><a id="user-content-ways-to-access-SEC-flings-data" class="anchor" href="https://github.com/Tradefeeds-Financial-data-API/SEC-Filings-API#ways-to-access-sec-filings-data" aria-hidden="true"></a>Ways to access SEC filings  data</h2>
<ul>
 	<li><strong>JSON REST API</strong></li>
 	<li><strong>Excel CSV download</strong></li>
 	<li><strong>PDF reports</strong></li>
 	<li><strong>Email link</strong></li>
</ul>

<h2>Documentation</h2>

Our <a href="https://tradefeeds.com/api-documentation/" rel="nofollow">documentation</a> includes input API filtering parameters, output response objects with explanation of their meaning. Clear request and response examples are given on the documentation page. Furthermore, we provide SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala

<h2>Request and response examples</h2>


<strong>Example 1: You are searching for data on 10-Q and 8-K filings of Apple.Inc.</strong>
<p><a href="https://tradefeeds.com/api-documentation/">https://tradefeeds.com/api/v1/secfilings?key=YOUR-KEY&stock_ticker_symbol=AAPL&year=2021</a></p>


    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            },
        "output": {
            "form_type": "10-Q"
            "title": "Quarterly Report [Sections 13 or 15(d)]"
            "link": "https://www.sec.gov/ix?doc=/Archives/edgar/data/0000320193/000032019321000056/aapl-20210327.htm"
            "filing_date": "2021-04-29"
            "reporting_date": "2021-03-27"
            },
            {
            "form_type": "8K"
            "title": "Quarterly Report [Sections 13 or 15(d)]"
            "link": "https://www.sec.gov/ix?doc=/Archives/edgar/data/0000320193/000032019321000056/aapl-20210327.htm"
            "filing_date": "2021-04-29"
            "reporting_date": "2021-03-27"
            },
            {
            "form_type": "10-Q"
            "title": "Quarterly Report [Sections 13 or 15(d)]"
            "link": "https://www.sec.gov/ix?doc=/Archives/edgar/data/0000320193/000032019321000056/aapl-20210327.htm"
            "filing_date": "2021-04-29"
            "reporting_date": "2021-03-27"

            },
        }



<strong>Example 2: You are searching for data on all 10-Q filings of Apple.Inc.</strong>

<p><a href="https://tradefeeds.com/api-documentation/">https://tradefeeds.com/api/v1/secfilings?key=YOUR-KEY&isin_identifier=US0378331005&form_type=10-Q</a></p>

    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            },
        "output": {
            "form_type": "10-Q"
            "title": "Quarterly Report [Sections 13 or 15(d)]"
            "link": "https://www.sec.gov/ix?doc=/Archives/edgar/data/0000320193/000032019321000056/aapl-20210327.htm"
            "filing_date": "2021-04-29"
            "reporting_date": "2021-03-27"
            },
            {
            "form_type": "10-Q"
            "title": "Quarterly Report [Sections 13 or 15(d)]"
            "link": "https://www.sec.gov/ix?doc=/Archives/edgar/data/0000320193/000032019321000056/aapl-20210327.htm"
            "filing_date": "2021-01-29"
            "reporting_date": "2020-12-27"
            },
            {
            "form_type": "10-Q"
            "title": "Quarterly Report [Sections 13 or 15(d)]"
            "link": "https://www.sec.gov/ix?doc=/Archives/edgar/data/0000320193/000032019321000056/aapl-20210327.htm"
            "filing_date": "2020-09-29"
            "reporting_date": "2020-08-27"
            },
            {
            "form_type": "10-Q"
            "title": "Quarterly Report [Sections 13 or 15(d)]"
            "link": "https://www.sec.gov/ix?doc=/Archives/edgar/data/0000320193/000032019321000056/aapl-20210327.htm"
            "filing_date": "2020-05-29"
            "reporting_date": "2020-04-27"
            },
        }
 

<h2>Customer support</h2>
In case that you encounter a data issue or you want to have more features added to the API, please contact us at support@tradefeeds.com.
 
<h2>Legal</h2>

<p> The use of Tradefeeds proprietary data and API database is subject to the&nbsp;<a href="https://tradefeeds.com/terms-and-conditions-on-data/">Tradefeeds Terms &amp; Conditions.</a></p>
