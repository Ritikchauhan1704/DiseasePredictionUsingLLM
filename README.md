Setup virtual env
pip install virtualenv
python -m venv myenv
myenv/Scripts/activate  //in cmd


Commands to run
pip install -r requirements.txt
uvicorn src.main:app --reload


Change loaction name in llm/main2.py
for symptom_precaution,symptoms_json,knowledge_json