# machine_learning_trading_bot

## Performance for current trading algorithm

![Alt text](Images/1%20SVM%20testing%20report.png)

![Alt text](Images/2%20Actual%20returns%20vs%20Strategy%20returns.png)

## Tuning the algorithm by adjusting the training dataset size

![Alt text](Images/3%20Classification%20report%20-%206%20months.png)

![Alt text](Images/4%20Plot%20-%206%20months.png)

**Question:** What impact resulted from increasing or decreasing the training window?

**Answer:** The accuracy level increased by 1% and the recall score also improved by 2% by increasing the training window to 6 months.

## Tuning the algorithm by adjusting the SMA input features

![Alt text](Images/5%20Classification%20report%20-%201%20month.png)

![Alt text](Images/6%20Plot%20-%201%20month.png)

**Question:** What impact resulted from increasing or decreasing either or both of the SMA windows?

**Answer:** The accuracy score and recall score remain constant by decreasing the training window to 1 month.

## Increasing both the short and long windows to 10 and 125 respectively

![Alt text](Images/7%20Classification%20report%20-%20Increasing%20short%20&%20long%20windows.png)

![Alt text](Images/8%20Plot%20-%20Increasing%20short%20&%20long%20windows.png)

**Question:** What impact resulted from increasing or decreasing either or both of the SMA windows?

**Answer:** The accuracy score and recall score both have increased by increasing the short window from 4 to 10 and increasing the long window from 100 to 125.

## Increasing only the short window to 6

![Alt text](Images/9%20Classification%20report%20-%20Increasing%20short%20window.png)

![Alt text](Images/10%20Plot%20-%20Increasing%20short%20window.png)

**Question:** What impact resulted from increasing or decreasing either or both of the SMA windows?

**Answer:** The accuracy score increased to 56% and the recall score increased to 99% by increasing the short window to 6.

## Increasing only the long window to 125

![Alt text](Images/11%20Classification%20report%20-%20Increasing%20long%20window.png)

![Alt text](Images/12%20Plot%20-%20Increasing%20long%20window.png)

**Question:** What impact resulted from increasing or decreasing either or both of the SMA windows?

**Answer:** The accuracy score and recall score, both increased by increasing only the long window to 125.

## Conclusion

Increasing the short window to 10 and long window to 125 for a 3 months training dataset produces the best set of parameters that give improved trading algorithm returns. Based on these parameters, accuracy score is 56% and recall score is 99%.

## Performance of the AdaBoost classifier

![Alt text](Images/13%20Classification%20report%20-%20AdaBoost%20model.png)

![Alt text](Images/14%20Plot%20-%20AdaBoost%20model.png)

**Question:** Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?

**Answer:** The accuracy score jumped to 85%. However, the recall score increased marginally to 0.97 as compared to the based model and decreased slightly as compared to the tuned model.