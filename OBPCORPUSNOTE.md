Cleaned Old Bailey Proceedings

<em>OBP</em> allows for the download of XML data of proceedings in batches of 10 via their own API. 
I downloaded the cases I wanted between the years 1664-1789 (90 total cases). 
Following a guide found on the <em>ProgrammingHistorian</em> I used my command line to install PIP and BeautifulSoup. 
I ran these programs on my data to extract the dates and text from the XML files so that they could be nicely put into a spreadsheet.

Though technically there are uncleaner versions of this data, I consider the XML data as the  "unclean" data set I was working with.

I had thought to use the image files embedded in the <em>OBP</em> website, but they used GIF format and those did not cleanly fit into any OCR even after conversion into JPEG or PDF. 
Mass downloading 90 images was also an issue as the way that the website was set up, WGET did not recgonize more than one link at a time, rendering it useless. 
