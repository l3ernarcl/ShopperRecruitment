# ShopperRecruitment
Hopefully a new angle to building an intelligent interface for admin to process and monitor Shopper Recruitment.

Begin with proper database modelling for the entire Shopper Recruitment process.
tableName = AptitudeTest
Fields:
- Timestamp_Apt DATE
- Name VARCHAR(50)
- NRIC VARCHAR(10) [PK]
- Email VARCHAR(100)
- Country (Dropdown will be ideal; handled by PHP form)
- Source (Dropdown will be ideal; handled by PHP form)
- Phonetype (Dropdown will be ideal; handled by PHP form)
- AptScore INT(2)
- Expiry TRUE/FALSE

tableName = VideoQuiz
Fields:
- Email VARCHAR(100) [PK, FK]
- Timestamp_Vid DATE
- Expiry TRUE/FALSE

tableName = RecruitData
