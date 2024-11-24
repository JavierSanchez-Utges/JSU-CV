# <<cv.name>>'s CV

((* if cv.phone *))
- Phone: <<cv.phone|replace("tel:", "")|replace("-"," ")>>
((* endif *))
((* if cv.email *))
- Email: [<<cv.email>>](mailto:<<cv.email>>)
((* endif *))
((* if cv.location *))
- Location: <<cv.location>>
((* endif *))
((* if cv.website *))
- Website: [<<cv.website|replace("https://","")|replace("/","")>>](<<cv.website>>)
((* endif *))
((* if cv.social_networks *))
    ((* for network in cv.social_networks *))
- <<network.network>>: 
  ((* if network.network == "LinkedIn" *))
    [<<network.username>>](https://www.linkedin.com/in/javier-sanchez-utges-6aa2961b3/)
  ((* elif network.network == "GitHub" *))
    [<<network.username>>](https://github.com/<<network.username>>)
  ((* elif network.network == "ORCID" *))
    [<<network.username>>](https://orcid.org/<<network.username>>)
  ((* elif network.network == "Google Scholar" *))
    [<<network.username>>](https://scholar.google.com/citations?user=YOUR_USER_ID)
  ((* else *))
    <<network.username>>
  ((* endif *))
    ((* endfor *))
((* endif *))
