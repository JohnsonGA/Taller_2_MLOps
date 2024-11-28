# Taller_2_MLOps

Swagger FastAPI de predicciones del Joblib
![image](https://github.com/user-attachments/assets/c91c830a-32f0-4ec5-ab22-b8cca3569bd8)

![image](https://github.com/user-attachments/assets/ceb755e8-a069-4eb9-b32e-8bb19de43121)

#Desplegamosen EC2

git clone https://github.com/JohnsonGA/CodingXPrience.git

sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update

sudo apt install python3.10
sudo apt install python3.10-venv python3-pip

# Crear y activar el entorno virtual
python3.10 -m venv mi_entorno
source mi_entorno/bin/activate

pip install -r requirements.txt

#Corremos el servicio temporalmente
python3 service.py
