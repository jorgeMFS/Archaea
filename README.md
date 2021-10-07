<p align="center">
<img src="img/archaea.png" alt="Panther" width="400" border="0" /></p>
<br>
<p align="center">
</p>

## INSTALL
Get Archaea project using:
```bash
git clone https://github.com/jorgeMFS/Archaea.git
chmod +x run.sh
bash run.sh 
```

## Using Docker

```sh
git clone https://github.com/jorgeMFS/Archaea.git
cd Archaea
docker-compose build
docker-compose up -d && docker exec -it archaea bash && docker-compose down
```

## Run Scripts
```bash
cd scripts || exit
bash prepare_and_classify_dataset.sh
```

## Requirements
- Ubunto 18.0 or higher
- Python3.6
- Anaconda
- or docker and docker-compose
