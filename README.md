# Web-Tech Project about Data Visualisation for Our Web technologies course.
   Required Components:
D3.js ://for data visualization . \
Dc.js\
Node.js\
Crossfilter.js\
Jquery\
MongoDB:\
Dataset Link : https://www.dropbox.com/s/cgt3vkdgvrvq3rt/dataset.rar?dl=0    \
MongoDB Tools: https://www.mongodb.com/try/download/database-tools.  \
   Steps for correct execution:\
     1.Install MongoDB,run mongod.exe\
     2.switch to new cmd terminal and Insert the data into mongoDB by typing code\
	    <pre>
	    C:\Program Files\MongoDB\Server\4.4\bin>mongoimport -d donorschoose -c projects --type csv --headerline --file C:\Users\[---adddress of dataset---]sampledata.csv.\
       P.S after MongoDB 4.4 version We need to download separately MongoDB Tools, therefore, install MongoDB Tools otherwise it will give error of \
              " mongoimport is not recognized as an internal or external command, operable program or batch file."\
        </pre>
	 3. open new cmd terminal and navigate to the node-dc-mongo directory using command prompt and run npm install, this will install the dependencies \
     4.Navigate to the node-dc-mongo directory using command prompt and run npm start\
     5.In your browser go to localhost:8080/index.html\
