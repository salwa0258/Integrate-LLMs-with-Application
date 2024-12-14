<h1 align="center"> Integrate LLMs with Application</h1>
<p align="center"> Penjelasan tentang bagaimana cara mengintegrasikan LLMs menggunakan API dan API with Streamlit </p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white">
<img src="https://img.shields.io/badge/IBM%20Cloud-1261FE?style=for-the-badge&logo=IBM%20Cloud&logoColor=white">
<img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white">


</div>
===================================================================================

```
```

**Instalation**
```bash
pip install -r requirements.txt
pip install streamlit
```
**Download file python scripts dengan mendownload pada link github :**
            <li>
              demo_wml_api.py <a href="https://github.com/ibm-build-lab/VAD-VAR-Workshop/blob/main/content/labs/Watsonx/WatsonxAI/files/201/applications/demo_wml_api.py" style="padding: 1px 5px; background-color: #007bff; color: white; text-decoration: none; border-radius: 8px; margin-right: 4px;">Original from IBM</a>
            <li>
              demo_wml_api_with_strealit.py <a href="https://github.com/ibm-build-lab/VAD-VAR-Workshop/blob/main/content/labs/Watsonx/WatsonxAI/files/201/applications/demo_wml_api_with_streamlit.py" style="padding: 1px 5px; background-color: #007bff; color: white; text-decoration: none; border-radius: 8px; margin-right: 4px;">Original from IBM</a></br>


**Buat file .env yang digunakan untuk API key dan Project ID**

 <pre><code>api_key=[your api key here]
project_id=[your project id here]</code></pre>

**Running Demo wml API dan API with Streamlit dengan cara :**

```bash
python ./demo_wml_api.py
streamlit run demo_wml_api_with_streamlit.py
```

**Hasil dari running tersebut adalah :**
    <li> demo_wml_api 
```bash
PS C:\Users\marso\Downloads\Tugas_LLMs> python ./demo_wml_api.py
---------------------------------------------------------------------------
Question/request: Write a paragraph about the capital of France.
Answer: Paris is the capital city of France and the largest city in France by population and area. Paris is the seat of the French National Assembly, the French Senate, the Conseil       de France, and the Paris City Council. Paris is the administrative center of the Paris metropolitan area and the center of the Île-de-France region.
---------------------------------------------------------------------------
C:\Users\marso\AppData\Roaming\Python\Python312\site-packages\ibm_watson_machine_learning\foundation_models\utils\utils.py:273: LifecycleWarning: Model 'meta-llama/llama-2-13b-chat'      is in deprecated state from 2024-08-26 until None. IDs of alternative models: None. Further details: https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/fm-model-            lifecycle.html?context=wx&audience=wdp
warnings.warn(default_warning_template.format(
---------------------------------------------------------------------------
Prompt: 
  From the following customer complaint, extract 3 factors that caused the customer to be unhappy. 
  Put each factor on a new line. 

    Customer complaint:
            I just tried to book a flight on your incredibly slow website.  All
            the times and prices were confusing.  I liked being able to compare
            the amenities in economy with business class side by side.  But I
            never got to reserve a seat because I didn't understand the seat map.
            Next time, I'll use a travel agent!


  Numbered list of all the factors that caused the customer to be unhappy:


List of complaints: 1. Slow website
  2. Confusing times and prices
  3. Lack of understanding of the seat map
---------------------------------------------------------------------------
--------------------------Invocation with REST-------------------------------------------
Question/request: Write a paragraph about the capital of France.
Answer: Paris (pronounced: ps-LAK) is the capital and largest city of France. It is a global city and one of the most popular tourist destinations in the world, with a estimated          10.17 million international tourist arrivals in 2014.
---------------------------------------------------------------------------
```
  <li> demo_wml_api_with_streamlit

![image Alt](https://github.com/Lalala0678/cona_coba/blob/a50d86c2a41c8a62791974e9991048c119722c72/Screenshot%202024-12-14%20131954.png)