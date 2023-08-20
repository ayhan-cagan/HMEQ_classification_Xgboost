# HMEQ_classification_Xgboost
The HMEQ (Home Equity) dataset contains features and default information for 5,960 home equity loans. A home equity loan is a type of loan where the borrower uses the equity of their home as collateral.

HMEQ (home equity - konut rehin) veri seti, 5.960 konut rehin kredisi için özellikleri ve temerrüt bilgilerini barındırır. Konut kredisi, borçlunun konutunun öz sermayesini temel teminat olarak kullandığı bir kredidir. 
Veri seti aşağıdaki özelliklere sahiptir:

◾ BAD: 1 = applicant defaulted on loan or seriously delinquent; 0 = applicant paid loan
◾ LOAN: Amount of the loan request
◾ MORTDUE: Amount due on existing mortgage
◾ VALUE: Value of current property
◾ REASON: DebtCon = debt consolidation; HomeImp = home improvement
◾ JOB: Occupational categories
◾ YOJ: Years at present job
◾ DEROG: Number of major derogatory reports
◾ DELINQ: Number of delinquent credit lines
◾ CLAGE: Age of oldest credit line in months
◾ NINQ: Number of recent credit inquiries
◾ CLNO: Number of credit lines
◾ DEBTINC: Debt-to-income ratio


◾ KÖTÜ: 1 = başvuru sahibi krediyi temerrüde düşürdü veya ciddi şekilde temerrüde düştü; 0 = başvuru sahibi tarafından ödenen kredi.  
◾ KREDİ: Kredi talebinin tutarı.  
◾ İpotek: Mevcut ipotek için ödenmesi gereken tutar.  
◾ DEĞER: Mevcut mülkün değeri.    
◾ NEDEN: DebtCon = borç konsolidasyonu; HomeImp = ev geliştirme.    
◾ İŞ: Meslek kategorileri.   
◾ YOJ: Şu anki işteki yılları.   
◾ DEROG: Büyük aşağılayıcı raporların sayısı.     
◾ DELINQ: Geciken kredi limitlerinin sayısı.     
◾ CLAGE: Ay cinsinden en eski kredi limitinin yaşı.    
◾ NINQ: Son kredi sorgularının sayısı.    
◾ CLNO: Kredi limiti sayısı.     
◾ DEBTINC: Borcun gelire oranı.  

The dataset presented a considerable number of missing values (NaNs). To address this, I employed data preprocessing techniques to handle these gaps and prepare the dataset for analysis. My objective was to solve a classification problem using machine learning algorithms. After exploring various algorithms and tuning hyperparameters, I identified the best-performing model for the task.

The ultimate goal of my project was to determine whether to grant a loan to a customer. I carefully documented my workflow, from data preparation to model selection and evaluation. Upon finalizing the model, I saved it for deployment and created a GitHub repository


