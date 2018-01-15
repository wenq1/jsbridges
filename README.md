## ReactNative/Weex Javascript Engine optimisations

This project uses [Duktape](www.duktape.org) embedded engine to reduce the size of Alibaba Weex significantly.


|                      | Original       | Reduced  | Reduction |
| ---------------------| --------------:| --------:| ---------:|
| armeabi/libweexv8.so | 3,583,820      | ~300k    |  >=10x    |

To build,

````
$ cd weex/android/sdk
$ ./gradlew assembleDebug
````

Further works include:

- experimenting with React Native and make a comparision.
- sample project to use the aar


