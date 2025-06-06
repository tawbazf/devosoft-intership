 npm install shaka-player
 mkdir video-streaming-backend
cd video-streaming-backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install fastapi python-jose[cryptography] passlib[bcrypt] boto3 python-multipart uvicorn
