Copy your xmodel to the board

### Steps for on board deployement
``bash
    pip install --upgrade pip wheel setuptools
    cd ~/yolonano
    pip install --user -r requirements_board.txt
    sudo chmod -R 777 code
    cd code
    python -m pip install --user -v -e . --no-build-isolation
    cd ..
    ```


