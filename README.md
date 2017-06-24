# SVM-Console LibSVM.Net example

This is an C# console example that uses LibSVM.Net and is modified
to detect sentiment in text strings. Think (I love you/I hate you/Glad to meet you)

Original work came from:
https://www.svm-tutorial.com/2014/10/svm-tutorial-classify-text-csharp/

I would suggest checking this guys site out to learn more about the theory of SVM's (Support Vector Machines)
I modified the example playing around with trying to detect spam. 

Compiling and Running:
You should use VS2015 set for 4.0 or above support (Linq) is used. I did not public the CsvData and LibSVM since
my hopes are you can use the given "package.config" and just tell Visual Studio to "Restore" the packages I 
used to get the code to work.

You will see a file named "spamdata.csv" in the root folder of the code. You will need to "copy" this file
to your build directory usually "bin\Debug" for the demo to work.

Thoughts:
When you run the application (if you get that far) you will be prompted to type something in,
I would start out with "Hello" and the maybe "I like you". You will then see the SVM prediction
for whether what you type is "Happy" "Normal" "Sad" and even "Angry"

I am not sure I changed the program enough to get the best results, but it's more interesting than
the original example that just says ists "sunny" or "rainy"

Have fun !!!!




