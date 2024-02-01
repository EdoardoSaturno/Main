/*
 * Copyright 2024 Edoardo Saturno
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *     http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */

1. Project Title
   - Human Values Classification with BERT-based Models

2. Project Description
   - In recent years, the advancement in classifying argumentative text into categories has seen significant progress. This project specifically focuses on the identification of four macro categories of "human values" – openness to change, self-enhancement, conservation, and self-transcendence. Leveraging pre-trained BERT models, particularly the "bert-base-uncased" model, the task involves employing distinct binary classification heads for each category.

3. Usage
   - Run the provided Python notebook in the repository. The notebook automates the installation of required packages using pip.

4. Data
   - The data used for this study was extracted from provided dataset, with a step to combine lower-order categories into macro categories. The dataset is organized into a Pandas DataFrame, including true labels for macro categories: Openness to change, Self-enhancement, Conservation, and Self-transcendence. 

5. Links to External Resources
   - [Identifying the Human Values behind Arguments Paper](https://aclanthology.org/2022.acl-long.306/)
   - [MELD Dataset for EDiRef](https://zenodo.org/records/6855004)
   - [AutoTokenizer - Hugging Face](https://huggingface.co/docs/transformers/model_doc/auto)

For detailed code and result analysis, refer to the "report" file in the repository.
