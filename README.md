# heart-felt
By: Michelle Juárez 

AI-generated art project for a major celebrity...

The purpose of this project is to produce AI art to reflect a user's most heartfelt emotion for the purpose of healing. The method by which this is accomplished is by first taking in about a paragraph's worth of text input from the user describing the memory/emotion. Next, that input is processed using a Bert Extractive Summarizer to summarize the input to a percentage of the original, providing us with enough key words and terms to provide as input for the next step.

Next, the summarized text is used as the input to generate a piece of AI art using the VQGAN+CLIP algorithm. The AI-generated image is then saved for the next step.

The final step in this process is to take the saved AI image and apply the Fast Style Transfer algorithm to the AI image using an example of the major celebrity's art as the style reference.

This project is developed as a proof of concept using open source libraries and packages, listed below, and has been implemented  in Google Colab. Updates to this project are expected to come as this idea evolves.

RESOURCES:

Bert Extractive Summarizer:
# Website: https://opensourcelibs.com/lib/bert-extractive-summarizer
# GitHub: https://github.com/dmmiller612/bert-extractive-summarizer

VQGAN+CLIP:
# Licensed under the MIT License
# Copyright (c) 2021 Katherine Crowson
#
# Permission is hereby granted, free of charge, to any person obtaining a copy
# of this software and associated documentation files (the "Software"), to deal
# in the Software without restriction, including without limitation the rights
# to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
# copies of the Software, and to permit persons to whom the Software is
# furnished to do so, subject to the following conditions:
#
# The above copyright notice and this permission notice shall be included in
# all copies or substantial portions of the Software.
#
# THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
# IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
# FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
# AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
# LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
# OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
# THE SOFTWARE.

Fast Style Transfer:
# Licensed under the Apache License, Version 2.0 (the "License");
# You may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
# https://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
