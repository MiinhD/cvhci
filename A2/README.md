## General info

See [nu vs epsilon](http://stats.stackexchange.com/a/167545/25741)


## SVM tests

Parameters: [docs](http://docs.opencv.org/3.0-beta/modules/ml/doc/support_vector_machines.html#svm-params-params)

* `cv::SVM::NU_SVR`, `nu=0.1`: 0.337434 online
* `cv::SVM::NU_SVR`, `nu=0.5`: 0.337434 online
* `cv::SVM::NU_SVR`, `nu=0.5`, `kernel_type = CvSVM::RBF`: 0.337434 online
* `cv::SVM::EPS_SVR`, `p=0.0`, `kernel_type = CvSVM::RBF`: Command terminated by signal (6: SIGABRT)
* `cv::SVM::EPS_SVR`, `p=0.2`, `kernel_type = CvSVM::RBF`: 0.337434 online
* `cv::SVM::EPS_SVR`, `p=0.3`, `kernel_type = CvSVM::RBF`: 0.337434 online
* `cv::SVM::EPS_SVR`, `p=0.5`, `kernel_type = CvSVM::RBF`: Command terminated by signal (6: SIGABRT)
* `cv::SVM::EPS_SVR`, `p=1.0`, `kernel_type = CvSVM::RBF`: Command terminated by signal (6: SIGABRT)
* `cv::SVM::EPS_SVR`, `p=1000.0`, `kernel_type = CvSVM::RBF`: Command terminated by signal (6: SIGABRT)
* `cv::SVM::C_SVC`, `gamma=0.10`, `C=1`, `kernel_type = CvSVM::RBF`: 0.877569
* `cv::SVM::C_SVC`, `gamma=0.15`, `C=1`, `kernel_type = CvSVM::RBF`: 0.891566
* `cv::SVM::C_SVC`, `gamma=0.19`, `C=1`, `kernel_type = CvSVM::RBF`: 0.870796
* `cv::SVM::C_SVC`, `gamma=0.20`, `C=1`, `kernel_type = CvSVM::RBF`: 0.899548
* `cv::SVM::C_SVC`, `gamma=0.20`, `C=10`, `kernel_type = CvSVM::RBF`: 0.90383
* `cv::SVM::C_SVC`, `gamma=0.20`, `C=100`, `kernel_type = CvSVM::RBF`: 0.90383
* `cv::SVM::C_SVC`, `gamma=0.30`, `C=1`, `kernel_type = CvSVM::RBF`: 0.89578
* `cv::SVM::C_SVC`, `gamma=0.30`, `C=100`, `kernel_type = CvSVM::RBF`: 0.90383
* `cv::SVM::C_SVC`, `gamma=0.50`, `C=1`, `kernel_type = CvSVM::RBF`: 0.893274
* `cv::SVM::C_SVC`, `gamma=0.80`, `C=1`, `kernel_type = CvSVM::RBF`: 0.865209
* `cv::SVM::C_SVC`, `gamma=0.90`, `C=1`, `kernel_type = CvSVM::RBF`: 0.837291
* `cv::SVM::C_SVC`, `gamma=1.10`, `C=1`, `kernel_type = CvSVM::RBF`: 0.827832
* `cv::SVM::C_SVC`, `kernel_type = CvSVM::LINEAR`: 0.856889