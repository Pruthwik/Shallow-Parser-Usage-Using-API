# The code is to be run in python3, not python2
# Install requests package, to install the package use the command below  
pip install requests
# How to run the code
- 2 steps involved
  * run_shallow_parser_api_and_save_to_file.py: Runs the shallow parser API and saved the SSF output into a file.
  * extract_data_from_ssf_in_conll_format_for_file.py: Convert the SSF into CONLL format based on the intended level.
  * Sample Run:  bash run_shallow_parser_and_convert_into_conll.sh input_file.txt hin 3
  * 7 languages supported: Language code in brackets
    + Hindi (hin)
    + Telugu (tel)
    + Kannada (kan)
    + Urdu (urd)
    + Malayalam (mal)
    + Tamil (tam)
    + Bengali (ben) 
- For more information about SSF, download the SSF guidelines from [here](https://verbs.colorado.edu/hindiurdu/guidelines_docs/ssf-guide.pdf)
- For tokenizers for Indian languages, use [our repo](https://github.com/Pruthwik/Tokenizer_for_Indian_Languages)
