```dataview 
TABLE
id,
title,
element,
category,
sub,
parent,
source,
status,
date,
tags
FROM "content/07-general-log"
WHERE file.name != "~ Log Index"
SORT id ASC
```