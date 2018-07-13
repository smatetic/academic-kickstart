+++
title = "ROTE: Rollback Protection for Trusted Execution"

# Date first published.
date = "2017-08-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Sinisa Matetic", "Ahmed Mansoor", "Kari Kostiainen",  "Aritra Dhar", "David Sommer", "Arthur Gervais", "Ari Juels", "Srdjan Capkun"]

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
publication = "In *26th Usenix Security Symposium*, Vancouver, Canada"
publication_short = ""

# Abstract and optional shortened version.
abstract = ""Intel SGX isolates the runtime memory of protected applications (enclaves) from the OS and allows enclaves to encrypt and authenticate (seal) data for persistent storage. Sealing prevents an untrusted OS from reading or arbitrarily modifying stored data. However, rollback attacks, where the adversary replays an old seal, remain possible. Data integrity violations through rollback can have severe consequences, especially for enclaves that operate on financial data. The SGX architecture was recently updated to support monotonic counters that may be used for rollback prevention, but we show that these counters have significant performance and security limitations. \n In this paper we propose a new approach for rollback protection on SGX. The intuition behind our approach is simple. A single platform cannot efficiently prevent rollback, but in many practical scenarios multiple processors can be enrolled to assist each other. We design and implement a rollback protection system called ROTE that realizes integrity protection as a distributed system among participating enclaves. We construct a model that captures the ability of the adversary to schedule the execution of protected applications, and show that our solution achieves a strong security property that we call *all-or-nothing rollback*: the only way to violate data integrity is to reset all participating platforms to their initial state. We implement ROTE and demonstrate that such a distributed rollback protection mechanism can be very fast.""


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
url_pdf = "https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-matetic.pdf"
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

#Further details on your publication can be written here using *Markdown* for formatting. This text will be displayed on the Publication Detail page.