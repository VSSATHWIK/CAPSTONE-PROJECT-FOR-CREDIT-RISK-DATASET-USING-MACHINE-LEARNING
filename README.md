700 good and 300 bad credits with 20 predictor variables. Data from 1973 to 1975. Stratified sample from actual credits with bad credits heavily oversampled. A cost matrix can be used. The 'South German Credit' data provide a correction and some background information, based on the Open Data LMU (2010) representation of the same data and several other German language resources. Variables

Column name: laufkont Variable name: status Content: status of the debtor's checking account with the bank (categorical)

Column name: laufzeit Variable name: duration Content: credit duration in months (quantitative)

Column name: moral Variable name: credit_history Content: history of compliance with previous or concurrent credit contracts (categorical)

Column name: verw Variable name: purpose Content: purpose for which the credit is needed (categorical)

Column name: hoehe Variable name: amount Content: credit amount in DM (quantitative; result of monotonic transformation; actual data and type of transformation unknown)

Column name: sparkont Variable name: savings Content: debtor's savings (categorical)

Column name: beszeit Variable name: employment_duration Content: duration of debtor's employment with current employer (ordinal; discretized quantitative)

Column name: rate Variable name: installment_rate Content: credit installments as a percentage of debtor's disposable income (ordinal; discretized quantitative)

Column name: famges Variable name: personal_status_sex Content: combined information on sex and marital status; categorical; sex cannot be recovered from the variable, because male singles and female non-singles are coded with the same code (2); female widows cannot be easily classified, because the code table does not list them in any of the female categories

Column name: buerge Variable name: other_debtors Content: Is there another debtor or a guarantor for the credit? (categorical)

Column name: wohnzeit Variable name: present_residence Content: length of time (in years) the debtor lives in the present residence (ordinal; discretized quantitative)

Column name: verm Variable name: property Content: the debtor's most valuable property, i.e. the highest possible code is used. Code 2 is used, if codes 3 or 4 are not applicable and there is a car or any other relevant property that does not fall under variable sparkont. (ordinal)

Column name: alter Variable name: age Content: age in years (quantitative)

Column name: weitkred Variable name: other_installment_plans Content: installment plans from providers other than the credit-giving bank (categorical)

Column name: wohn Variable name: housing Content: type of housing the debtor lives in (categorical)

Column name: bishkred Variable name: number_credits Content: number of credits including the current one the debtor has (or had) at this bank (ordinal, discretized quantitative); contrary to Fahrmeir and HamerleÃ¢â‚¬â„¢s (1984) statement, the original data values are not available.

Column name: beruf Variable name: job Content: quality of debtor's job (ordinal)

Column name: pers Variable name: people_liable Content: number of persons who financially depend on the debtor (i.e., are entitled to maintenance) (binary, discretized quantitative)

Column name: telef Variable name: telephone Content: Is there a telephone landline registered on the debtor's name? (binary; remember that the data are from the 1970s)

Column name: gastarb Variable name: foreign_worker Content: Is the debtor a foreign worker? (binary)

Column name: kredit Variable name: credit_risk Content: Has the credit contract been complied with (good) or not (bad) ? (binary)
