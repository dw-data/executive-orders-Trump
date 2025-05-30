# Trump's unprecedented use of executive orders

Idea, data analysis, visualization, writing: Gianna-Carina Grün

Interviews: Benjamin Alvarez Gruber

Data consolidation: Janelle Dumalaon, Kira Schacht

Editing: Milan Gagnon


# Data sources & processing

Data was last pulled from all sources on April 28, 2025.

You can review it in [this Google Sheet](https://docs.google.com/spreadsheets/d/1KrxeJ5sPvirGUhL9i0E4QmwiMQg5O8odtTOBXdEGuLg/edit?usp=sharing)

## Executive orders

Data on executive orders were mainly taken from [Federal Register](https://www.federalregister.gov/presidential-documents/executive-orders/donald-trump/2025). The Federal Register was chosen mainly over [WhiteHouse.gov](https://www.whitehouse.gov/presidential-actions/), because the Federal Register also includes metadata such as the EO number that allows to cross-reference this database with others. This was essential for example to evaluate which executive orders have been legally challenged.

As there is a slight time delay between the publication on the White House website and the Federal Register, two executive orders were pulled directly from the White House website prior to publication of the article to contain the most recently available information.

## Legal Challenges

Data on legal challenges to the Trump Administration was drawn from the [Litigation Tracker by Just Security](https://www.justsecurity.org/107087/tracker-litigation-legal-challenges-trump-administration/). Just Security is an online publication by digital law and policy journal at the Reiss Center on Law and Security at New York University School of Law.

Executive orders were extracted from their dropdown menu and matched to the list of executive orders from the previous section via the executive order number assigned by the Federal Register.

Additionally, the page as manually scanned for mentions of executive orders for further validation. This resulted in four additional classifications: 14190 mentioned in Case No. 1:25-cv-10548, 14195 mentioned in Case No. 3:25-cv-00464, 14242 mentioned in the header before Case No. 1:25-cv-10601, 14251 mentioned in Case No.1:25-cv-01030.

For the last data update prior to publication, the 11 executive order numbers mentioned Case No. 1:25-cv-00077-N/A were also tagged manually as legally challenged. This case references [12 US states issuing a complaint](https://storage.courtlistener.com/recap/gov.uscourts.cit.17091/gov.uscourts.cit.17091.2.0_1.pdf) against several tariff-related executive orders, arguining it is not within presidential powers to impose tariffs.

While the Litigation Tracker differentiates between different types of legal challenges, we did not make any distinction between different types such as temporary restraining orders (TRO),  other motions, petitions or complaints. Whenever any of such cases was in relation to an executive order, that order was subsequently manually tagged as legally challenged in our database.

Each executive order that is marked legally challenged, has one or more cases relating to it listed in Just Security's Litigation Tracker.

If any of the closed cases was in reference to an executive order, we double-checked that there were additional cases still open in relation to that order.



## Topic clustering

Topic clustering was inspired by filters used by the [NYTimes](https://www.nytimes.com/interactive/2025/us/trump-agenda-2025.html) and clusters used by [CBS News](https://www.cbsnews.com/news/trump-issues-record-100-executive-order-of-second-term-breakdown/), based on which we developed our own clusters that are included in the list below

Each executive order can be tagged to belong to several clusters, and in fact, one EO rarely only falls into one category. They were tagged both, according to the argumentation used in the document as well as with regards to the implications a directive would have.

To arrive at the final tagging, three journalists individually tagged each executive order based on the list of available clusters. Initial mismatches were mostly based on one person assigning more tags than another person, rather than based on dissonance what cluster an EO was belonging to. Any mismatch in tagging was revised and adjusted.

* Economy and resources
* Education
* Environment/Energy/Climate
* Foreign Policy and Security
* Freedom of expression
* Gender/Diversity/Equity/Inclusion
* Government
* Health/Healthcare/Abortion
* Home Affairs/Domestic policy
* Immigration and citizenship
* Military
* Religion and antisemitism
* Social Media and technology
* Tariffs
* Trade
* Other
