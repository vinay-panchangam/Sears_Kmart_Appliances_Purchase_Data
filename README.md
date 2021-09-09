# Sears Kmart Appliances Data

## Data Dictionary

Dataset 1

Column Name | Description
------------ | -------------
GID | Deduped hashed ID for a member
CID | Hashed member loyalty ID – same member can have multiple of these
tran_dt | Transaction date
shc_soar_nm | Business unit name
prod_intrnl_nbr | Product internal number
srs_dvsn_nbr | Sears division number
srs_item_nbr | Sears item number
online_ord_nbr_ind | Online order indicator
brnd_nm | Brand name
appliance | Appliance name
appliance_group | Appliance group
locn_nbr | Store location number
locn_city | Store location city
locn_st_cd | Store location state
zip_cd | Store location zip
zip_pls_4 | Store location zip plus 4
age_year | Age of appliance in years
age_month | Age of appliance in months
unit_qty | Unit quantity sold
gross_sales | Goss sale amount
net_sales | Net sale amount
points_earn | Reward points earned
points_burn | Reward point burned


Dataset 2

Column Name | Description
------------ | -------------
GID | Deduped hashed ID for a member
CID | Hashed unique ID for Sears Home Services customers – same member could have multiple of these.
AGR_SUF_NO | Agreement suffix number. Unique number assigned for each agreement of a customer.
CUR_ITM_CVR_QT | Number of items covered in the agreement. Protection Agreement can cover multiple items and this value indicates that. By default Home Warranty covers up to 10 appliances in a home and it shows 0 for these contracts.
SVC_PRD_CD | Service Product Code: indicates the type of contract. PA1: Protection Agreement. HWP: Home Warranty
AGR_CNC_IND_FL | Indicator for agreement cancellation before its expiry. (Y/N)
SL_DT | Agreement sale date.
CUR_STA_DT| Agreement start date.
CUR_EPR_DT | Agreement expiry date, adjusted for cancellations.
ORI_EPR_DT | Original agreement expiry date.
MTH_CVR_NO_QT | Agreement duration at the time of sale, indicated for PAs and as 0 for HW.
ITM_SUF_NO | Unique number assigned to the appliance covered. HS_CUS_NO + ITM_SUF_NO gives a uinque ID for an appliance.
CUR_STA_DT_ITEM | Start date of agreement on the appliance when multiple appliances are covered in a PA.
CUR_EPR_DT_ITEM | Expiry date of agreement, adjusted for cancellations, for the appliance when multiple appliances are covered in a PA.
ORI_EPR_DT_ITEM | Original expiry date of agreement for the appliance when multiple appliances are covered in a PA.
MTH_CVR_NO_QT_ITEM | Agreement duation corresponding to the appliance when multiple appliances are covered in a PA.
AGR_ITM_STS_CD | Agreement status code corresponding to the appliance when multiple appliances are covered in a PA.
CNC_DT | Cancellation date corresponding to the appliance when multiple appliances are covered in a PA.
SL_DT_ITEM | Sale date corresponding to the appliance when multiple appliances are covered in a PA.
APPLIANCE | Type of appliance covered.
PSV_ITM_MDL_NO | Appliance model number.
PRD_ITM_NO | Sears product number.
PSV_MDS_SRL_NO | Serial number.
MFG_BND_NM | Brand

Dataset 3

Column Name | Description
------------ | -------------
GID | Deduped hashed ID for a member
CID | Hashed unique ID for Sears Home Services customers – same member could have multiple of these.
SOID | Service order ID
DIFFICULTY_LEVEL | Difficulty level of the service order
SO_CRT_DT | Service order create date
SO_STS_CD | Service order status code
SO_STS_DT | Service order status date
SVC_ORD_CLO_DT | Service order close date
SERVICETYPE | Service type
PAY_MET | Payment method
PAYMENT_TYP_GRP | Payment type group
AGR_SUF_NO | Agreement suffix number
ITM_SUF_NO | Item suffix number
PRD_ITM_NO | Product item number
PSV_ITM_MDL_NO | Model number
PSV_MDS_SRL_NO | Product serial number
N_ATP | Number of attempts
CYCLE_TIME | Serivice order cycle time
PARTS_REQUIRED | Number of parts required in the service order
PARTS | Number of parts required in the service order
PARTS_USED | Number of parts used in the service order
PARTS_INSTALLED | Number of parts installed in the service order
RESCHEDULES | Number of reschedules for the service call
FST_PRT_ORD_DT | First part ordered date
LST_PRT_ORD_DT | Last part ordered date
PRT_SEQ_NO | Part sequence number
PRT_NO | Part number
SVC_PRT_QT | Service part quantity
PRT_SEL_PRC_AM | Part sell price amount
ORI_PRT_PRC_AM | Original part parice amount




