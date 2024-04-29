Very quick tech demo of Umbraco V13 utilizing a combination of different Bootstrap templates to showcase a fictional company. 
Emphasis on using Umbraco Blockgrids and Blocklists and every single element being editable within Umbraco. 

Estimated time of completion: 8 hours. 
This was my first venture into ASP.NET Core and Umbraco V13. Very transferrable skillset from this short demo. 
Was fun to utilize my prior experience and knowledge and to prove that a lot of what i've learned can be reapplied. 

Biggest challenge was the Blockgrid custom renderer; this was the 'newest' thing I had to learn and was most unfamiliar with. (Content Grid on previous versions of Umbraco, only a small overlap though!)
Given 3 possible choices of rendering this (built-in renderer, a razor template + macro or full custom) I opted for a full custom renderer, this was the most complicated and the least documented, but I prevailed nonethless. 
The result of this is a truly bespoke and fully developer controlled design of when and where the code renders, ensuring access to all relevant Umbraco fields. 
It also prevents the need for template files, macros, etc. So the project is a lot easier to manage. 

The Umbraco Blocklist is used for a carousel header, allowing the customer to have a header that can be as simple as a single image; to one that has an image with header text followed by subheader text with an internal / external link with customisable link text. Additionally, they can change text colour and apply a dark background tint  to make text more legible if the image used is too bright. 

The Umbraco Blockgrid is used 3x times in small slightly changing use cases, but the gist of it is used when there's repeating main content. Whether it's a 2x2 or 1x3 or 2x3. 
A customised grid layout has been designed to allow images, rte and headers. In addition to utilizing the base Umbraco elements provided such as just a rte or just a header.
