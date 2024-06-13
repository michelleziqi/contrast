---
layout: page
title:  "Project"
---
<link rel='stylesheet' href='https://use.fontawesome.com/releases/v5.7.0/css/all.css' integrity='sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ' crossorigin='anonymous'>
<style>
    .project {
        padding-top: 15px;
        padding-bottom: 15px;
    }
    h4 {
        padding-left: 20px;
        color: #f0a1a8;
    }
    .project a.main-nav-item {
        text-decoration: none;
        transition: color 0.3s linear;
        -webkit-transition: color 0.3s linear;
        -moz-transition: color 0.3s linear;
    }
    .project a.main-nav-item:hover {
        color: #ed5a65;
        text-decoration: none;
    }
    .main-nav-item {
        display: inline-block;
    }
    .title {
        display: table;
    }
    .fa-file-alt,
    h4 {
        display: table-cell;
        vertical-align: top;
    }
    .fa-terminal,
    p {
        margin-left: 40px;
        word-wrap: break-word;
    }
    .fa-terminal {
        color: #999;
    }
    .fa-file {
        margin-left: 45px;
        word-wrap: break-word;
        color: #999;
    }
    @media only screen and (max-width: 568px) {
        .fa-file .fa-file {
            margin-left: 10px;
        }
    }
    .fancy-link {
        text-decoration: none;
        transition: color 0.3s linear;
        -webkit-transition: color 0.3s linear;
        -moz-transition: color 0.3s linear;
    }
    .fancy-link:hover {
        color: #ed5a65;
    }
</style>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script>
    $(function() {
        $('.project').hide();
        $('div.project').each(function(i) {
            $(this).delay(i * 800).fadeIn('slow');
        });
    });
</script>
<div class="project">
    <div class="title">
        <i class='fas fa-file-alt' style='font-size:24px'></i>
        <h4><a class="fancy-link" href="https://scholar.uwindsor.ca/major-papers/139/">Economic Growth and Water Pollution in the Circum-Bohai-Sea Zone in China - An Environmental Kuznets Curve Analysis</a></h4>
    </div>
    <p>Based on the principle and model of Environmental Kuznets Curve (EKC), the present paper examines the relationship between water pollution and economic growth in the Circum-Bohai-Sea Zone of Beijing, Tianjin, Hebei Province, Shandong Province, and Liaoning Province with the annual time series data for 2003 to 2017. By analyzing the industrial, household, and total wastewater discharge separately as the measurement of water pollution, the results are consistent with the EKC model. In particular, according to econometric analysis, the variables of economic growth and per capita GDP are statistically significant in domestic and total wastewater discharge cases. However, the association of industrial wastewater discharge and economic development is more significant in the N-type EKC model, according to estimation results. This implies that water pollution will worsen without increased government interventions and management. The sub-goal is to investigate the impact of technologies on the EKC model in each subregion. By using the number of universities as a proxy of technology and observing the turning point, it can be assumed that technology can help decrease the level of water pollution, though trends in Shandong Province challenge this finding.</p>
    <i class='far fa-file'></i>
    <a class="main-nav-item" href="https://scholar.uwindsor.ca/major-papers/139/">Report</a>
</div>

<!-- Project 2 -->
<div class="project">
    <div class="title">
        <i class='fas fa-file-alt' style='font-size:24px'></i>
        <h4>The Determinants of Healthcare Expenditure in Canada </h4>
    </div>
    <p>Designed a multivariable regression with dummy variable to examine the determinants of healthcare expenditure in Canada, test the validity of the regression model and investigate the short-run and long-run impacts in time series data</p>
</div>

<!-- Project 3 -->
<div class="project">
    <div class="title">
        <i class='fas fa-file-alt' style='font-size:24px'></i>
        <h4>Credit Credit Fraud Detection</h4>
    </div>
    <p> This project is mainly to apply ML techniques to credit card fraud detetion. The output is 'class' labelling, which takes the value of 1 for fraud, and 0 for no fraud. The input are time which means the seconds elapsed between the first transaction in the data set and the subsequent transactions, transaction amount, and principal components obtained using PCA. Based on the exporatory data analysis, there are a total of 284,807 transactions, but there are 492 transactions are fraudulent. Therefore, we could see this dataset is highly unbalanced, with the positive class accounting for 0.172% of total transactions. In addition, when evaluating the data quality, there is no missing data in the dataset. Moreover, I splitted the data into train and test data, then I started to build models. I created and compared six models, they are (1)Logistic regression model for both L1 and L2; (2)KNN model (3)Tree Model (4)Random Forest (5)XGBoot Model (6)SVM model. I peformed cross validation with RepeatedKFold and StratifiedKFold to check which model has best results. Based on Accuracy and ROC value, logistic regression with L2 regulatrisation has provided best results for cross validation with both RepeatedKFold and StratifiedKFold techniques. However, the.... We used both SMOTE and ADASYN Oversampling method to handle with class imbalance. After running the models on oversampled data, XGBOOST model .... Finally, I conducted hyperparameter tuning to XGBoost model.  </p>
</div>










