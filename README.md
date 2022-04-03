<h1><center>API Protected with oauth2</center></h1>

<h2>Testing example:</h2>

1. Install your own venv
~~~bash
python3 -m venv ./
source bin/activate
~~~
2. Install requirements
~~~bash
pip install -r requirements.txt
~~~
3. Run server
~~~bash
# main is file name without extension
hypercorn example:app --reload
~~~