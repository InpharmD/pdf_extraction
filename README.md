# pdf_table_extraction
Extract Content and Tables from PDF as json

# Write a Python library to extract all sections and tables as json format from any given PDF. It should work for any PDF without any issues

 ```
    "response": {
          "title": "PDF Title/Document Title",
          "section1": "Section1 content",
          "section2": "Section2 content",
          "section3": "Section2 content",
          "tables": [
                    "table1": {
                        "title": "table title",
                        "column1": [value1,value2,value3...],
                        "column2": [value1,value2,value3...],
                        .....
                        "columnN": [value1,value2,value3...],
                    }
                 ]
     }
  ```
 
 Some sample PDF's attached

 [10.1007@s40261-020-00939-x.pdf](https://github.com/InpharmD/pdf_table_extraction/files/13479699/10.1007%40s40261-020-00939-x.1.pdf)
 [1-s2.0-S1936879816318465-main.pdf](https://github.com/InpharmD/pdf_table_extraction/files/13479743/1-s2.0-S1936879816318465-main.1.pdf)
[10.1007@s11239-019-01846-5.pdf](https://github.com/InpharmD/pdf_table_extraction/files/13479781/10.1007%40s11239-019-01846-5.pdf)
[10.1002@hep4.1293.pdf](https://github.com/InpharmD/pdf_table_extraction/files/13479780/10.1002%40hep4.1293.pdf)
[nihms-1735236.pdf](https://github.com/InpharmD/pdf_table_extraction/files/13479785/nihms-1735236.pdf)
[mohan2017.pdf](https://github.com/InpharmD/pdf_table_extraction/files/13479784/mohan2017.pdf)
[mehringer2018.pdf](https://github.com/InpharmD/pdf_table_extraction/files/13479783/mehringer2018.pdf)
[karkouti_2021_oi_210145_1616616524.51622.pdf](https://github.com/InpharmD/pdf_table_extraction/files/13479782/karkouti_2021_oi_210145_1616616524.51622.pdf)
[pereira2017.pdf](https://github.com/InpharmD/pdf_table_extraction/files/13479786/pereira2017.pdf)

PS. Please do not use adobe PDF extraction API
