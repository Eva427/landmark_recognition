# Landmark Recognition
------------------------------------------------------

# Description & Objectives 
------------------------------------------------------

The objective of this project is to precisely identify globally renowned landmarks or points of interest within an image. This task is accomplished through Supervised Learning, with a model trained on a comprehensive dataset of images labeled with their corresponding landmarks. The selected landmarks are summarized in the following table : 

<div align="center">

<table>
  <tr>
    <th>Monument name</th>
    <th>Location</th>
    <th>Monument name</th>
    <th>Location</th>
  </tr>
  <tr>
    <td>Petra Treasury</td>
    <td>Jordan</td>
    <td>Burj Khalifa</td>
    <td>UAE</td>
  </tr>
  <tr>
    <td>Alhambra</td>
    <td>Spain</td>
    <td>Brandenburg Gate</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Hagia Sophia</td>
    <td>Turkey</td>
    <td>Opera House</td>
    <td>Australia</td>
  </tr>
  <tr>
    <td>Acropolis of Athens</td>
    <td>Greece</td>
    <td>Neuschwanstein Castle</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Burj Al Arab</td>
    <td>Dubai, UAE</td>
    <td>Angkor Wat</td>
    <td>Cambodia</td>
  </tr>
  <tr>
    <td>Chichen Itza</td>
    <td>Mexico</td>
    <td>Kremlin</td>
    <td>Russia</td>
  </tr>
  <tr>
    <td>Statue of Liberty</td>
    <td>United States</td>
    <td>Colosseum</td>
    <td>Italy</td>
  </tr>
  <tr>
    <td>Parthenon</td>
    <td>Greece</td>
    <td>Sagrada Familia</td>
    <td>Spain</td>
  </tr>
  <tr>
    <td>Christ the Redeemer</td>
    <td>Brazil</td>
    <td>Pyramids of Giza</td>
    <td>Egypt</td>
  </tr>
  <tr>
    <td>MachuPicchu</td>
    <td>Peru</td>
    <td>Eiffel Tower</td>
    <td>France</td>
  </tr>
</table>
</div>

<div align="center">
  
**Table of the selected landmarks for model training**

</div>
Finally, the model's goal is to analyze an input image and determine whether it contains a particular landmark, and if so to correctly identify which landmark it is by giving a probability score denoting its confidence level in the prediction. 

# Github Organization : 
------------------------------------------------------
**1. Code file : contains all the code developped for the projet:**
- **Collect data**
    - data_collect.js : simulate a right-click event to collect image URLs 
      
- **Utilities**
    - data_loading.py : load the pictures
    - data_preparation_for_models.py : prepare the data fir the model 

- **Model Training and Testing**
    - model_training.py : train the model 
    - model_testing.py : test and assess the model
  
**2. Data file : contains all the pictures used for training the model**
    Each file of the **Data** file has the name of the corresponding landmark
