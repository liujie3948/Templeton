# Templeton
Automatically render a mustache or glasses over an image of a face

## Examples

### Mustache

    src/templeton -m img/hillary_clinton.jpg img/mustache.png img/hillary_mustache.png

![alt tag](https://raw.githubusercontent.com/kallaballa/Templeton/master/img/hillary_mustache.png)
### Glasses

    src/templeton -g img/hillary_clinton.jpg img/glasses.png img/hillary_glasses.png

![alt tag](https://raw.githubusercontent.com/kallaballa/Templeton/master/img/hillary_glasses.png)

## Build

    # clone repository
    git clone https://github.com/kallaballa/Templeton.git
    
    # build dlib
    cd third/
    tar -xf dlib-19.0.tar.bz2
    cd dlib-19.0
    sudo python setup.py install
    
    # build Templeton
    cd ../..
    wget http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
    bunzip2 shape_predictor_68_face_landmarks.dat.bz2
    make
    

