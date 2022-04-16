# Detecção de defeitos em conectores USB
Projeto para detecção de defeitos em conectores USB com Raspberry Pi e TensorFlow Lite.

- Configurar [Raspberry Pi](https://projects.raspberrypi.org/en/projects/raspberry-pi-setting-up/1).

- Conectar e configurar [Pi Camera](https://www.raspberrypi.com/documentation/computers/configuration.html).

- Crie um Ambiente Virtual Python:
```
sudo -H python3 -m pip install virtualenv
mkdir project
cd project
python3 -m virtualenv env
source env/bin/activate
```

- Instale pip:
```
pip install --upgrade pip
```

- Clonar repositório:
```
git clone https://github.com/mdsfernandes/Deteccao_de_defeitos_em_conectores_USB
cd Deteccao_de_defeitos_em_conectores_USBc/image_classification
```

- Instale bibliotecas de requisitos:
```
pip install -r requirements.txt
sudo apt-get install libatlas-base-dev
```

- Executar modelo:
```
python3 classify.py \
  -- model ~/ai/modelos/modeloA.tflite
```
