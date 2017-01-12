## Synopsis  
  
This is the Python 3
[snowball-stemmer](https://pypi.python.org/pypi/snowballstemmer) package with
Arabic light stemming capabilities. The Arabic light stemmer extension is
supposed to work, but the installation is buggy. This repo has built in Arabic
capabilities. Stay tuned for Pashto stemming capabilities.  
  
## Code Example  
  
```

import snowballstemmer  


ar_light_stem = snowballstemmer.stemmer('arabic')  


print(ar_light_stem.stemWord(u'المقاومة'))

```

  
## Motivation  
  
Since IST has been embarking on the effort to improve text mining capabilities
in multiple languages, this internal package is intended to provide value to our
Topic Modeling solution and be a hub for linguistic research and development.
Arabic was the initial milestone, but Pashto (in the near future) and other
languages such as Farsi/Dari (longer term) should be added to this package.  
  
## Installation  
  
To be updated...  
  
## API Reference  
  
To be updated...  
  
## Tests  
  
To be updated...  
  
## Contributors  
  
If you can develop another language and add it, that would be great. You can
also improve on the currently existing stemming algorithms.  
  
\#\# License  
  
To be updated...
