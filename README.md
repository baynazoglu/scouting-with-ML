
# Talent Scouting Classification with Machine Learning

<img src="https://github.com/baynazoglu/scouting-with-ML/blob/main/scouting.jpg" alt="Image" width="700" height="420">


## Business Problem

This project aims to predict the class (average, highlighted) of players based on the ratings given by scouts on the players' characteristics.

## Dataset Story

The dataset consists of information on football players observed during matches, including the evaluations made

 by scouts on players' characteristics and their ratings.

### _attributes.csv

This dataset contains 8 variables and 10,730 observations. The descriptions of the variables are as follows:

- task_response_id: Set of evaluations by a scout for all players in a team's squad during a match
- match_id: ID of the respective match
- evaluator_id: ID of the evaluator (scout)
- player_id: ID of the respective player
- position_id: ID of the position played by the respective player in that match
  - 1: Goalkeeper
  - 2: Center-back
  - 3: Right-back
  - 4: Left-back
  - 5: Defensive midfielder
  - 6: Central midfielder
  - 7: Right winger
  - 8: Left winger
  - 9: Attacking midfielder
  - 10: Striker
- analysis_id: Set of feature evaluations by a scout for a player in a match
- attribute_id: ID of each evaluated attribute of the players
- attribute_value: Value (rating) given by a scout to a player's attribute

### _potential_labels.csv

This dataset contains 5 variables and 322 observations. The descriptions of the variables are as follows:

- task_response_id: Set of evaluations by a scout for all players in a team's squad during a match
- match_id: ID of the respective match
- evaluator_id: ID of the evaluator (scout)
- player_id: ID of the respective player
- potential_label: Label indicating the final decision of a scout regarding a player in a match (target variable)

  ## Installation

1. Clone this project: `git clone https://github.com/YOUR_USERNAME/Feature-Engineering.git`
2. Navigate to the project directory: `cd Feature-Engineering`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the project: `python main.py`

## Usage

1. Add the dataset to the "data" folder.
2. Run the project files.
3. Perform data analysis and feature engineering steps.
4. Develop a machine learning model to predict whether individuals have diabetes or not.
5. Evaluate the model's performance and analyze the results.

## Contributing

1. Fork this project.
2. Create a new branch: `git checkout -b feature/NewFeature`
3. Make your changes and commit them: `git commit -am 'Added a new feature'`
4. Push your branch to the forked repository: `git push origin feature/NewFeature`
5. Create a pull request.


----------



# Makine Öğrenmesi ile Yetenek Avcılığı(Scouting) Sınıflandırma

## İş Problemi

Bu proje, scout'ların futbolcuların özelliklerine verilen puanlara göre oyuncuların hangi sınıfa (average, highlighted) ait olduğunu tahminlemeyi hedeflemektedir.

## Veri Seti Hikayesi

Veri seti, maçlarda gözlemlenen futbolcuların özelliklerine dayanarak scout'ların değerlendirdiği futbolcuların özelliklerini ve puanlarını içeren bilgilerden oluşmaktadır.

### _attributes.csv

Bu veri seti, 8 değişken ve 10.730 gözlemden oluşmaktadır. Aşağıda değişkenlerin açıklamaları verilmiştir:

- task_response_id: Bir scout'un bir maçta bir takımın kadrosundaki tüm oyunculara dair değerlendirmelerinin kümesi
- match_id: İlgili maçın kimliği
- evaluator_id: Değerlendiricinin (scout'un) kimliği
- player_id: İlgili oyuncunun kimliği
- position_id: İlgili oyuncunun o maçta oynadığı pozisyonun kimliği
  - 1: Kaleci
  - 2: Stoper
  - 3: Sağ bek
  - 4: Sol bek
  - 5: Defansif orta saha
  - 6: Merkez orta saha
  - 7: Sağ kanat
  - 8: Sol kanat
  - 9: Ofansif orta saha
  - 10: Forvet
- analysis_id: Bir scout'un bir maçta bir oyuncuya dair özellik değerlendirmelerini içeren küme
- attribute_id: Oyuncuların değerlendirildiği her bir özelliğin kimliği
- attribute_value: Bir scout'un bir oyuncunun bir özelliğine verdiği değer (puan)

### _potential_labels.csv

Bu veri seti, 5 değişken ve 322 gözlemden oluşmaktadır. Aşağıda değişkenlerin açıklamaları verilmiştir:

- task_response_id: Bir scout'un bir maçta bir takımın kadrosundaki tüm oyunculara dair değerlendirmelerinin kümesi
- match_id: İlgili maçın kimliği
- evaluator_id: Değerlendiricinin (scout'un) kimliği
- player_id: İlgili oyuncunun kimliği
- potential_label: Bir scout'un bir maçta bir oyuncuyla ilgili nihai kararını belirten etiket (hedef değişken)

## Kurulum

1. Bu projeyi klonlayın: `git clone https://github.com/YOUR_USERNAME/Feature-Engineering.git`
2. Proje dizinine gidin: `cd Feature-Engineering`
3. Gerekli bağımlılıkları yükleyin: `pip install -r requirements.txt`
4. Projeyi çalıştırın: `python main.py`

## Kullanım

1. Veri setini "data" klasörüne ekleyin.
2. Proje dosyalarını çalıştırın.
3. Veri analizi ve özellik mühendisliği adımlarını gerçekleştirin.
4. Makine öğrenmesi modeli geliştirerek, kişilerin diyabet hastası olup olmadığını tahmin edin.
5. Modelin performansını değerlendirin ve sonuçları analiz edin.

## Katkıda Bulunma

1. Bu projeyi fork edin.
2. Yeni bir dal oluşturun: `git checkout -b feature/YeniOzellik`
3. Değişikliklerinizi yapın ve bunları kaydedin: `git commit -am 'Yeni bir özellik eklendi'`
4. Dalınızı forked repository'e gönderin: `git push origin feature/YeniOzellik`
5. Bir pull isteği oluşturun.




