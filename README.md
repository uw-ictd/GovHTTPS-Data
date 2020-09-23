# HTTPS Adoption Measurement in Governments Worldwide

This is the public dataset published as auxilary material for the paper accepted 
to Internet Measurement Conference (IMC'20) titled "Accept the Risk and Continue: 
Measuring the Long Tail of Government https Adoption"

The dataset is present in `dataset.csv` and includes the whitelist of the websites
which were obtained as a part of the whitelist process both manually and crowdsourcing 
using Mechanical Turk. The countries and their domain country codes are available in
`country-extensions.csv` file. A breakdown of the same dataset split by country is available
in the `country/` directory.


### Accept the Risk and Continue: Measuring the Long Tail of Government https Adoption

*By: Sudheesh Singanamalla, Esther Han Beol Jang, Richard Anderson, Tadayoshi Kohno, and Kurtis Heimerl*

```bib
@inproceedings{10.1145/3419394.3423645,
    author = {Singanamalla, Sudheesh and Jang, Esther Han Beol and Anderson, Richard and Kohno, Tadayoshi and Heimerl, Kurtis},
    title = {Accept the Risk and Continue: Measuring the Long Tail of Government https Adoption},
    year = {2020},
    isbn = {978-1-4503-8138-3/20/10},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    url = {https://doi.org/10.1145/3419394.3423645},
    doi = {10.1145/3419394.3423645},
    booktitle = {Proceedings of the Internet Measurement Conference},
    location = {Virtual Event},
    series = {IMC '20}
}
```

or

```text
Sudheesh Singanamalla, Esther Han Beol Jang, Richard Anderson, Tadayoshi Kohno, and Kurtis Heimerl. 2020. 
Accept the Risk and Continue: Measuring the Long Tail of Government https Adoption. In ACM Internet 
Measurement Conference (IMC ’20), October 27–29, 2020, Virtual Event, USA. ACM, New York, NY, USA, 
21 pages. https://doi.org/10.1145/3419394.3423645
```

Want to help us curate more government websites to the dataset? Please send a pull request.

---

Note: The filters applied in the process of curation of this dataset could include entries which 
are very intentionally close to official government extensions eg. `abcgov.us` instead of `abc.gov.us` as 
indicated in the paper. We do our best to filter them (eg. `trivago.ccTLD` which matches `go.ccTLD` extensions)
in our analysis in the paper but some errors could have crept in. We however leave these entries in this dataset
as is and do not remove them for any future work on phishing detections.
