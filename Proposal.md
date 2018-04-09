{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf200
{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;\red27\green31\blue34;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c14118\c16078\c18039;\cssrgb\c100000\c100000\c100000;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid1\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid101\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid2}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}}
\margl1440\margr1440\vieww14200\viewh11380\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\b\fs64 \cf2 \cb3 \expnd0\expndtw0\kerning0
Proposal\cb1 \
\pard\pardeftab720\partightenfactor0

\fs32 \cf2 \cb3 Title:
\b0  Breast Cancer Screening \'97 Predicting whether a mammogram mass is benign or malignant\
\cb1 \

\b \cb3 Problem:
\b0  \cf2 \cb3 The project will focus on mammography which is considered the most effective method for detecting breast cancer. The problem is that the low positive predictive value of breast \
\pard\tx720\pardeftab720\partightenfactor0
\cf2 biopsy resulting from mammogram interpretation leads to approximately \
70% unnecessary biopsies with benign outcomes. \
\cf2 \cb1 \
\pard\pardeftab720\partightenfactor0

\b \cf2 \cb3 Who might care?
\b0  \cf2 \cb3 Physicians and hospitals around the world can use such a model to predict whether a mammogram mass is benign or malignant. Patients can have a better diagnosis and avoid unnecessary biopsies. Better predictions can help both the physician and patient to reduce costs in case of negligence due to unnecessary expenses or lawsuits due to wrong diagnosis.\
\cf2 \cb1 \

\b \cb3 Data:
\b0  \cf2 \cb3 The Mammographic Mass Data Set has been acquired from the UCI repository. \cf0 \cb3 This data contains 961 instances of masses detected in mammograms, and contains the following attributes:\
\pard\tx720\pardeftab720\partightenfactor0
\cf0 \cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0\cf0 \cb3 \kerning1\expnd0\expndtw0 {\listtext	1.	}\expnd0\expndtw0\kerning0
BI-RADS assessment: 1 to 5 (ordinal)\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 {\listtext	2.	}\expnd0\expndtw0\kerning0
Age: patient's age in years (integer)\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 {\listtext	3.	}\expnd0\expndtw0\kerning0
Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 {\listtext	4.	}\expnd0\expndtw0\kerning0
Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 {\listtext	5.	}\expnd0\expndtw0\kerning0
Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 {\listtext	6.	}\expnd0\expndtw0\kerning0
Severity: benign=0 or malignant=1 (binominal)\cf2 \cb3 \
\pard\pardeftab720\partightenfactor0
\cf2 \

\b Approach:
\b0  \cf2 \cb3 A supervised classification algorithm is a good choice to build a predictive model of a set of categories, in this case, benign or malignant. The dataset contains missing values so the first step should be to take care of them. Exploratory data analysis will help understand the data. Finally, different algorithmic models will be used to find the best accuracy possible; this includes neural networks.\
\cf2 \cb1 \

\b \cb3 Deliverables:
\b0 \cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls2\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 {\listtext	1.	}\expnd0\expndtw0\kerning0
Code: loading data, data cleaning, exploratory data analysis, machine learning algorithms.\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 {\listtext	2.	}\expnd0\expndtw0\kerning0
Report on the project\
\pard\tx720\pardeftab720\partightenfactor0
\cf2 \
 \
}