## Repository for the ACL 2022 paper: <br> Incorporating Stock Market Signals for Twitter Stance Detection

Link to the paper: [Incorporating Stock Market Signals for Twitter Stance Detection](https://github.com/cambridge-wtwt/acl2022-wtwt-stocks)

Please use the following citation:

```
@inproceedings{conforti2022stocks,
          title={Incorporating Stock Market Signals for Twitter Stance Detection},
          author={Conforti, Costanza and Berndt, Jakob and Pilehvar, Mohammad Taher and Giannitsarou, Chryssi and Toxvaerd, Flavio and Collier, Nigel} 
          booktitle={Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (ACL2022)},
          year={2022}
        }
```

<br>

### Dataset

This data extend the Will-They-Won't-They (WT-WT) dataset. WT-WT is a large dataset of English tweets targeted at stance detection for the rumor verification task. The dataset is constructed based on tweets that discuss five recent merger and acquisition (M&A) operations of US companies, mainly from the healthcare sector.

For the four healthcare mergers, we obtain historical prices in 30-min intervals for the involved stocks. Each entry in the data has the following fields: *DateTime, Open, High, Low, Close, Volume*. DateTime is in US Eastern Time, in the format ``YY-MM-DD h:m:s``. Only minutes with trading volume are included: times with zero volume, such as during weekends or holidays, are omitted. Prices are adjusted for dividends and splits.

<br>

### Considered M&A operations


| Operation | Buyer       | Target            | Industry
| ---       | ---         | ---               | ---
| CVS_AET   | CVS Health  | Aetna             | Healthcare
| CI_ESRX   | Cigna       | Express Scripts   | Healthcare
| ANTM_CI   | Anthem      | Cigna             | Healthcare
| AET_HUM   | Aetna       | Humana            | Healthcare

<br>

### Contacts

- {cc918, jb2088, mp792, cg349, fmot2, nhc30} @cam.ac.uk
- [Cambridge Language Technology Lab](http://ltl.mml.cam.ac.uk/people/)
- [Cambridge Faculty of Economics](http://www.econ.cam.ac.uk/)
