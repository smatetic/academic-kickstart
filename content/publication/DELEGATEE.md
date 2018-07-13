+++
title = "DelegaTEE: Brokered Delegation Using Trusted Execution Environments"

# Date first published.
date = "2018-07-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Sinisa Matetic", "Moritz Schneider", "Kari Kostiainen", "Andrew Miller", "Ari Juels", "Srdjan Capkun"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *27th Usenix Security Symposium*, Baltimore, USA"
publication_short = ""

# Abstract and optional shortened version.
abstract = "We introduce a new concept called *brokered delegation*. Brokered delegation allows users to flexibly delegate credentials and rights for a range of service providers to other users and third parties. We explore how brokered delegation can be implemented using novel trusted execution environments (TEEs). We introduce a system called DelegaTEE that enables users (Delegatees) to log into different online services using the credentials of other users (Owners). Credentials in DelegaTEE are never revealed to delegatees and owners can restrict access to their accounts using a range of rich, contextually dependent delegation policies. DelegaTEE fundamentally shifts existing access control models for centralized online services. It does so by using TEEs to permit access delegation *at the user's discretion*. DelegaTEE thus effectively reduces mandatory access control (MAC) in this context to discretionary access control (DAC). The system demonstrates the significant potential for TEEs to create new forms of resource sharing around online services without the direct support from those services. We present a full implementation of DelegaTEE using Intel SGX and demonstrate its use in four real-world applications: email access (SMTP/IMAP), restricted website access using a HTTPS proxy, e-banking/credit card, and a third-party payment system (PayPal)."


abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
#url_pdf = "pdf/my-paper-name.pdf"
url_pdf = "https://www.usenix.org/conference/usenixsecurity18/presentation/matetic"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
