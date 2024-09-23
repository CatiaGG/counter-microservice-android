# counter-microservice-android

I've modified the branch 'completed_code', which handle the deployment of the microservice provided by mimik 'randomnumber_v1' for the generation of random numbers. 
With the apported changes, the application will communicate with the new microservice 'counter-microservice', with the call "http:/127.0.0.1:%d%s/counter?counter=counterValue", every time the 'Increase the Counting' button from the user interphace is pressed, increasing the value of counterVale of 1. 
In the other repository called 'counter-microservice' there's the project of the new microservice to let a counter to increase of 1 each time the 'Increase the Counting' button on the user interphace is pressed.
