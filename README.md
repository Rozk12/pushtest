# hi-ASBrake-14thLine
This project mainly consists of three parts; Image Pro, PLC and python codes.

PLC and Image Pro could be dummy with setting is_dummy=True in main.py.

[Google Drive](https://drive.google.com/drive/folders/1BlFZ-6t7gujefl7jr913m6RFaZghW3uE?usp=drive_link)

## Python codes
### Install     
    python -m venv venv
    venv/Script/activate.bat
    pip install -r requirements.txt 

### Run
Check is_dummy in src/main.py

Run

    python src/main.py
    
## Image Pro    
- [recipi](https://drive.google.com/drive/folders/13EkHD-2eaMV_-UOR9Y7cgQIXeHikluvl?usp=drive_link), [model](https://drive.google.com/drive/folders/1nA9lXoif6Jk-CSZz0r-tl_Jnn52rJQEC?usp=drive_link)

- Instead of using camera, sample images in [material](https://drive.google.com/drive/folders/1rV2F1CRhpizKVWalZ5TmrEp1j669ZB2o?usp=drive_link) could be used.

### Dummy
In src/main.py, set `is_dummy = True`

## PLC
### Dummy
In src/main.py, set `is_dummy = True`

Open a new terminal and run

    python src/dummy_plc.py

Go to http://127.0.0.1:9100/docs

Select a scenario
