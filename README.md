# **Vietnamese ID Card Extractor - Developed by Nguyen Phan Nhut Truong N20DCCN082**

## **Introduction**

An web application helps us to extract information from Vietnamese chip-based ID card in a second. This application aims to reduce human typing workload and saves more time.

## **Installation**
All requirement libraries are listed in requirements.txt. You can install it by using:

``` bash
# Virtual env recommended
pip install -r requirements.txt
```
or build through **[Docker](https://www.docker.com/)** by:

```
docker build -t <app_name> .
```

## **Usage**

``` python
python run.py
```
With Docker:
```
docker run -p 8080:8080 <app_name>
```

## **Demo**
![demo](demo.png)

## **TODO**
- [ ] Implement eKYC features.
- [ ] Improve speed of detection (Imma update newer version of YOLO).
- [ ] Improve accuracy of text recognized.
- [ ] Improve ability to align ID card in different light conditions.
- [ ] Code Refactoring

