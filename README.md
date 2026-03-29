# Summer-Olympics-Medal-statistics-1896-2024-Olympic Games Dashboard

This project is an interactive Power BI dashboard built to analyze Olympic Games data from multiple perspectives, including medals, sports, athletes, countries, and gender-based participation.

The dashboard was designed to transform raw Olympic data into a clear and visually engaging analytical report that helps identify key trends and performance patterns across different sports and countries.

Project Objectives

The main goal of this project is to provide an analytical view of Olympic data and answer questions such as:

Which sports have the highest number of medals won?
Which countries perform best across different sports?
How does medal distribution change by sport and year?
What are the trends in athlete participation over time?
How does gender representation differ across Olympic sports?
Tools Used
Power BI – data modeling, DAX measures, dashboard design
SQL / Data Preparation – data cleaning and structuring
Excel / CSV dataset – source data
DAX – calculated measures and analytical logic
Data Model

The dashboard is built using a star schema structure:

Fact_Medals – main fact table containing medal-level records
Dim_Country – country information
Dim_Sport – sport and event categories
Dim_Year – year and season
Dim_Athlete – athlete information
_Measures – dedicated table for DAX measures

This structure improves performance, simplifies calculations, and supports interactive filtering.

Key Features
Total medals analysis
Top sports by medals won
Country-level medal performance
Gender-based analysis of athletes and medals
Trend analysis by year
Interactive filters for country, sport, gender, year, and medal type
Clean Olympic-themed visual design
Example Insights

The dashboard allows users to quickly identify:

the most successful sports for a selected country
sports with the highest medal activity
long-term Olympic participation trends
differences between male and female athlete representation
distribution of medals across sports and countries

ეს პროექტი წარმოადგენს Power BI-ში შექმნილ ინტერაქტიულ დეშბორდს, რომელიც მიზნად ისახავს ოლიმპიური თამაშების მონაცემების ანალიზს სხვადასხვა ჭრილში — სპორტი, ქვეყნები, მედლები, სპორტსმენები და გენდერი.

დეშბორდი აერთიანებს მონაცემთა ანალიტიკასა და ვიზუალიზაციას, რაც მომხმარებელს საშუალებას აძლევს მარტივად დაინახოს ძირითადი ტენდენციები და შესრულების შედეგები.

პროექტის მიზანი

პროექტის მთავარი მიზანია ოლიმპიური მონაცემების ანალიტიკური წარმოდგენა და პასუხის გაცემა შემდეგ კითხვებზე:

რომელ სპორტის სახეობებში არის ყველაზე მეტი მედალი მიღებული?
რომელი ქვეყნები არიან ყველაზე წარმატებულები?
როგორ იცვლება მედლების განაწილება წლების მიხედვით?
როგორია სპორტსმენების მონაწილეობის ტენდენცია?
რა განსხვავებაა ქალებისა და კაცების მონაწილეობასა და შედეგებში?
გამოყენებული ტექნოლოგიები
Power BI – მონაცემთა მოდელირება და ვიზუალიზაცია
SQL / მონაცემთა დამუშავება – მონაცემების გაწმენდა და სტრუქტურირება
Excel / CSV – საწყისი მონაცემები
DAX – ანალიტიკური measure-ები
მონაცემთა მოდელი

დეშბორდი აგებულია Star Schema სტრუქტურაზე:

Fact_Medals – ძირითადი ფაქტობრივი ცხრილი (მედლების დონეზე მონაცემები)
Dim_Country – ქვეყნების ინფორმაცია
Dim_Sport – სპორტისა და დისციპლინების კატეგორიები
Dim_Year – წელი და სეზონი
Dim_Athlete – სპორტსმენების მონაცემები
_Measures – DAX measure-ების ცხრილი

ეს სტრუქტურა უზრუნველყოფს:

სწრაფ მუშაობას
მარტივ ანალიზს
ინტერაქტიულ ფილტრაციას
ძირითადი ფუნქციები
მედლების საერთო ანალიზი
Top სპორტების იდენტიფიკაცია მედლების მიხედვით
ქვეყნების მიხედვით შესრულების შეფასება
გენდერული ანალიზი
დროითი ტენდენციების ანალიზი
ინტერაქტიული ფილტრები (ქვეყანა, სპორტი, წელი, გენდერი, მედლის ტიპი)
ოლიმპიური თემატიკის დიზაინი
ანალიტიკური მიგნებები

დეშბორდი საშუალებას იძლევა:

დავინახოთ კონკრეტული ქვეყნის ყველაზე ძლიერი სპორტები
გამოვავლინოთ სპორტები, სადაც ყველაზე მეტი მედალია გათამაშებული
გავაანალიზოთ მონაწილეობის ზრდა დროთა განმავლობაში
შევადაროთ ქალებისა და კაცების შედეგები
შევაფასოთ მედლების განაწილება სპორტებსა და ქვეყნებს შორის
