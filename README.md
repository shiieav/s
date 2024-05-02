* {
  box-sizing: border-box;
}

body {
  background-color: #c9d2fc;
}

.cat-head {
  position: absolute;
  right: 0;
  left: 0;
  top: 0;
  bottom: 0;
  margin: auto;
  background: linear-gradient(#5e5e5e 85%, #45454f 100%);
  width: 205px;
  height: 180px;
  border: 1px solid #000;
  border-radius: 46%;
}

.cat-left-ear {
  position: absolute;
  top: -26px;
  left: -31px;
  z-index: 1;
  border-top-left-radius: 90px;
  border-top-right-radius: 10px;
  transform: rotate(-45deg);
  border-left: 35px solid transparent;
  border-right: 35px solid transparent;
  border-bottom: 70px solid #5e5e5e;
}

.cat-right-ear {
  position: absolute;
  top: -26px;
  left: 163px;
  z-index: 1;
  transform: rotate(45deg);
  border-top-left-radius: 90px;
  border-top-right-radius: 10px;
  border-left: 35px solid transparent;
  border-right: 35px solid transparent;
  border-bottom: 70px solid #5e5e5e;
}

.cat-left-inner-ear {
  position: absolute;
  top: 22px;
  left: -20px;
  border-top-left-radius: 90px;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 40%;
  border-bottom-left-radius: 40%;
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
  border-bottom: 40px solid #3b3b4f;
}

.cat-right-inner-ear {
  position: absolute;
  top: 22px;
  left: -20px;
  border-top-left-radius: 90px;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 40%;
  border-bottom-left-radius: 40%;
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
  border-bottom: 40px solid #3b3b4f;
}

.cat-left-eye {
  position: absolute;
  top: 54px;
  left: 39px;
  border-radius: 60%;
  transform: rotate(25deg);
  width: 30px;
  height: 40px;
  background-color: #000;
}

.cat-right-eye {
  position: absolute;
  top: 54px;
  left: 134px;
  border-radius: 60%;
  transform: rotate(-25deg);
  width: 30px;
  height: 40px;
  background-color: #000;
}

.cat-left-inner-eye {
  position: absolute;
  top: 8px;
  left: 2px;
  width: 10px;
  height: 20px;
  transform: rotate(10deg);
  background-color: #fff;
  border-radius: 60%;
}

.cat-right-inner-eye {
  position: absolute;
  top: 8px;
  left: 18px;
  transform: rotate(-5deg);
  width: 10px;
  height: 20px;
  background-color: #fff;
  border-radius: 60%;
}

.cat-nose {
  position: absolute;
  top: 108px;
  left: 85px;
  border-top-left-radius: 50%;
  border-bottom-right-radius: 50%;
  border-bottom-left-radius: 50%;
  transform: rotate(180deg);
  border-left: 15px solid transparent;
  border-right: 15px solid transparent;
  border-bottom: 20px solid #442c2c;
}

.cat-mouth div {
  width: 30px;
  height: 50px;
  border: 2px solid #000;
  border-radius: 190%/190px 150px 0 0;
  border-color: black transparent transparent transparent;
}

.cat-mouth-line-left {
  position: absolute;
  top: 88px;
  left: 74px;
  transform: rotate(170deg);
}

.cat-mouth-line-right {
  position: absolute;
  top: 88px;
  left: 91px;
  transform: rotate(165deg);
}

.cat-whiskers-left div {
  width: 40px;
  height: 1px;
  background-color: #000;
}

.cat-whiskers-right div {
  width: 40px;
  height: 1px;
  background-color: #000;
}

.cat-whisker-left-top {
  position: absolute;
  top: 120px;
  left: 52px;
  transform: rotate(10deg);
}

.cat-whisker-left-middle {
  position: absolute;
  top: 127px;
  left: 52px;
  transform: rotate(3deg);
}

.cat-whisker-left-bottom {
  position: absolute;
  top: 134px;
  left: 52px;
  transform: rotate(-3deg);
}

.cat-whisker-right-top {
  position: absolute;
  top: 120px;
  left: 109px;
  transform: rotate(-10deg);
}

.cat-whisker-right-middle {
  position: absolute;
  top: 127px;
  left: 109px;
  transform: rotate(-3deg);
}

.cat-whisker-right-bottom {
  position: absolute;
  top: 134px;
  left: 109px;
  transform: rotate(3deg);
}
