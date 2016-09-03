Installation scripts for Jetson TX1 and Jetson TK1.

Install Caffe with Web Demo for Jetson TX1 - 32bit
$ git clone https://github.com/ferhatkurt/Jetson.git
$ cd Jetson
$ chmod +x JetsonTX1_Caffe_with_Demo.sh
$ ./JetsonTX1_Caffe_with_Demo.sh

Installation can continue more then 5 hours and sometimes you need to enter password ubuntu.

After installation open a new terminal and run 
$ python ~/caffe/examples/web_demo/app.py -g

Then open browser and type http://localhost
