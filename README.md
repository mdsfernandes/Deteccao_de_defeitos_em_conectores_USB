# Detecção de defeitos em conectores USB
Projeto para detecção de defeitos em conectores USB com Raspberry Pi e TensorFlow Lite.

- Configurar [Raspberry Pi](https://projects.raspberrypi.org/en/projects/raspberry-pi-setting-up/1).

- Conectar e configurar [Pi Camera](https://www.raspberrypi.com/documentation/computers/configuration.html).

- Crie um [Ambiente Virtual Python](https://docs.python.org/pt-br/3/library/venv.html).

- Instale pip:
```
pip install --upgrade pip
```

- Clonar repositório:
```
git clone https://github.com/mdsfernandes/Deteccao_de_defeitos_em_conectores_USB && cd Deteccao_de_defeitos
```

- Instale bibliotecas de requisitos:
```
pip install -r requirements.txt
sudo apt-get install libatlas-base-dev
```

- Executar modelo:
python3 classify.py \
  --model modeloA.tflite
