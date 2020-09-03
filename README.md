# python_cpp_communication
Call Python file through CPP wrapper

Below is Path User need to change in pyCPP.cpp file order to run this source code.
- in pyCPP.cpp file line number 12. User need to provide tensorflow 2.2 path. Note that User need to provide path in "\\" format
std::string tensoflow_env = "C:\\Users\\PRATIK\\anaconda3\\envs\\tensorflow_GPU\\"

 ## Common Configuration setting 
  - This source code requried visual studio 2015 with v140 compiler.
  - This source code only run in Release mode with x64 configuration.

  --> User need to change Include directory and linker  path in visual studio.
      Right Click to Solution --> Property Manager --> C/C++  --> additional include directory . Change to user specified tensorflow 2.2 folder path as mention in below         example then click Ok button.
      Example --> <Tensorflow_2.2_path>\include
    
      Right Click to Solution --> Property Manager --> Linker  --> additional Library directory . Change to user specified tensorflow 2.2 folder.
      Example --> <Tensorflow_2.2_path>\libs
      
 ## System enviornment setting 
  --> User have to set below path in system environment path variable in windows. then only above code will work.
      <Tensorflow_env22>
      <Tensorflow_env22>\Scripts
      <Tensorflow_env22>\Library\bin
    
    


