1.calculate_parameters�ļ��У�

    1.1 ��beginΪǰ׺��py�ļ���ͨ��wind�����ݽӿ��������ݴ洢�����ص�mysql���ݿ��У�
        ��õ��������ݱ�:table_day_data��table_month_data��
    
    1.2 ��calculateΪǰ׺��py�ļ��Ǽ��������Լ������ӿ⣬���Ѽ���Ľ���洢��1.1�е�table_month_data���ݱ��С�
    
    1.3 recover_month_data.py�������޸�����1.1��1.2֮������ݱ�
    
    1.4 ��stocks��ͷ��py�ļ��������洢����300����֤500�Ĺ�Ʊ��Ϣ��
    
    1.5 deal_with_day_data.py���ṩһЩ�����Ĺ��ܺ�����

2.clean�ļ��У�

    2.1 add_industry_dummy_variables.py�ǰ���ҵ������ӵ�table_month_data���ݱ���

    2.2 get_clean_store_data.py��table_month_data�е����ݽ�����ϴ�õ�һ���µ����ݱ�all_stocks_cleaned_factors_table��
        final_clean.py�Ƕ�all_stocks_cleaned_factors_table�е����ݽ�����ϴ�õ�һ���µ����ݱ�final_all_stocks_cleaned_factors_table

    2.3 auto_regression_tvalue_correlation.py�Ǽ���õ�tֵ��icֵ��
        auto_regression_improved_correlation.py�Ƕ�icֵ���㷽���Ľ��󣬵õ���icֵ

3.backtest�ļ��У�

    3.1 tmp.py���лز⣬�ڿ���̨�����ÿ����ĩѡ���Ĺ�Ʊ��ϣ�������и�����Ʊ�������ʣ��Լ����������������ʣ�
        �����Ƴ�2010�굽2016�������ʵ�����ͼ��



ע�⣺�ز��в��õľ��ǵ�Ȩ��