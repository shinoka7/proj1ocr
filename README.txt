Setup Leptonica: (Steps in Cygwin Terminal)
Step1: mkdir -p /opt/src && /opt/src
Step2: tar -xvf leptonica-1.76.0.tar.gz
Step2.5: cd leptonica-1.76.0
Step3: ./configure --without-giflib
Step4: make
Step5: make install
Step6: make clean

OCR Usage
Step1: (In terminal) cd to the directory of this file
Step2: Run in the commandline 
	'tesseract -l eng [inputimage filename] [outputbase name]'
Step3: The input image file should be in .tif format, and there is an example provided in the package
Step4: The Outputbase should be generated in the same directory containing text






The code in this repository is licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENCE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
