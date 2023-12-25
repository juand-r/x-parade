# x-parade
This repo contains the dataset for [X-PARADE: Cross-Lingual Textual Entailment and Information Divergence across Paragraphs](https://arxiv.org/abs/2309.08873)

The data is contained in json files with the following format:

```json
{
    "tokens": {"0":"ES:", "1": "Los", "2": "primeros", "3": "colleges"},
    "text": "Los primeros colleges ...",
    "pair_type": "en-es",
    "premise": "Cambridge has 31 colleges, two of which, Murray Edwards and Newnham, ...",
    "pageid": "25978572",
    "title": "Universidad de Cambridge",
    "similarity": 0.8476878405,
    "annotations": [
                    {"annotator_id":0,
                     "comment": "The English version states that Lucy Cavendish was previously...",
                     "spans": {"new information": [1,2,3,4],
                               "new information (inferable)": [65, 66, 67, 68, 69, 70],
                               "connotation difference": []
                              }
                    },
                    {"annotator_id":1,
                     "comment": null,
                     "spans": {"new information": [1,2,3,4,5],
                               "new information (inferable)": [66, 67, 68],
                               "connotation difference": []
                              }
                    }
                    ],
}
```
