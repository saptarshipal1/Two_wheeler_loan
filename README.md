# Two_wheeler_loan

Dataset: https://www.kaggle.com/datasets/yashkmd/credit-profile-two-wheeler-loan-dataset

This dataset provides a comprehensive overview of potential loan applicants' profiles, specifically tailored for the Indian demographic. It encapsulates a range of features, from basic demographics to financial details, that can be instrumental in assessing the creditworthiness of an individual.

Age:
Type: Integer
Description: Represents the age of the applicant. Indicates the applicant's maturity level.
Range: 18 to 70

Gender:
Type: Categorical
Description: Gender of the applicant.
Categories: Male, Female, Other

Income:
Type: Integer
Description: The applicant's income, which is critical in assessing their ability to repay the loan.
Range: Multiples of 1000's

Credit Score:
Type: Integer
Description: A score quantifying the applicant's creditworthiness based on their credit history.
Range: 300 to 850

Credit History Length:
Type: Integer
Description: Represents the number of months since the applicant's first credit line. Indicates the applicant's experience with credit management.
Units: Months

Number of Existing Loans:
Type: Integer
Description: The number of loans the applicant currently has.
Range: 0 to 10

Loan Amount:
Type: Integer
Description: The amount of money the applicant is requesting.
Range: 0 to 150,000

Loan Tenure:
Type: Integer
Description: The number of months the applicant wants to repay the loan over.
Units: Months

Existing Customer:
Type: Categorical
Description: Whether the applicant is an existing customer of the finance company.
Categories: Yes, No

State:
Type: Categorical
Description: The state in India where the applicant resides.
Categories: Maharashtra, Delhi, Karnataka, Tamil Nadu, West Bengal, Uttar Pradesh, Gujarat, Rajasthan, Kerala, Telangana, etc.

City:
Type: Categorical
Description: The city or village in India where the applicant resides.
Categories: Mumbai, Pune, New Delhi, Bengaluru, Chennai, Kolkata, Ahmedabad, Jaipur, Kochi, Hyderabad, and various villages.

LTV Ratio:
Type: Float
Description: The loan-to-value ratio, represents the ratio of the loan amount to the appraised value of the asset (typically a house). Higher LTVs can indicate higher risk.
Range: 40% to 95%

Employment Profile:
Type: Categorical
Description: General employment category of the applicant.
Categories: Salaried, Self-Employed, Freelancer, Unemployed, Student

Occupation:
Type: Categorical
Description: Specific occupation or job title of the applicant.
Categories: Software Engineer, Doctor, Teacher, Business Owner, Writer, etc.

Profile Score:
Type: Integer
Description: A score ranging from 0 to 100 represents the overall profile of the applicant based on the actual loan repayment data. Higher values indicate better profiles.
Range: 0 to 100
