# Travel-Reimbursement-Approval-Agent
Quick Run Commands
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python -m rag.ingest
python -m uvicorn app:app --reload

Open another terminal:

venv\Scripts\activate
streamlit run ui/streamlit_app.py
