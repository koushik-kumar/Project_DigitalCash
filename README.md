{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf600
{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;\red53\green53\blue53;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c27059\c27059\c27059;\cssrgb\c100000\c100000\c100000;}
\margl1440\margr1440\vieww25780\viewh13380\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\fs28 \cf2 \cb3 \expnd0\expndtw0\kerning0
Current project is designed using python\'a03.8.0\cb1 \
\cb3 There may be a need to install a few python\'a0packages from pypl (python package library).\cb1 \
\cb3 a. BitVector\cb1 \
\cb3 b.\'a0pycryptodome==3.4.3\cb1 \
\
\cb3 If there is an error for missing package library, please install\'a0using:\cb1 \
\cb3 pip3 install <package_name>\cb1 \
\
\cb3 Step 1:\cb1 \
\cb3 Open Three Terminals or three tabs in a terminal.\cb1 \
\
\cb3 Step 2:\cb1 \
\cb3 i. In terminal one load Bank function\cb1 \
\cb3 ii. In terminal two load Customer function\cb1 \
\cb3 iii. In terminal three load Merchant function\cb1 \
\
\cb3 Step 3:\cb1 \
\cb3 Follow steps in the terminal for Customer Function. (No user inputs are needed for Bank and Merchant Functions)\
\
On generating a new money order, the signed money order details are stored in file SIGNED_MO.txt in Customer directory.\
On Successfully debiting a Money Order the details of money order (unique_id and identity informations) are stored in bank_database.csv in Bank Directory.\
\
To create a cheating scenario, this file can be edited to duplicate MO information or to corrupt money order.\cb1 \
If any-errors are seen during the usage of signed money order, please clean all data in SIGNED_MO.txt and execute all three programs again.}
