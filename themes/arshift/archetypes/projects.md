+++
project_name = "{{ replace .Name "-" " " | title }}"
title = "{{ replace .Name "-" " " | title }}"
date = {{ .Date }}
start_year = '{{ time.Now.Format "2006" }}'
end_year = '{{ time.Now.Format "2006" }}'
images = []
address = ""
project_type = ""
client = ""
company = "ARshift Sarl | Entreprise totale"
credit_architect_advisor = ""
credit_ingeneer_carpenter = ""
credit_photographer = ""
keywords = ["général", "bois", "rénovation"]
draft = false
+++