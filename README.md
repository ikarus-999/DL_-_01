# DL_-_01
머신러닝_잘모르는거정리
# How 2 preprocess 2 diff dataframe columns
# 컬럼이 다른 두 DataFrame 정리하기
'''
train_columns = list(x_train.columns.unique())
test_columns = list(x_test.columns.unique())
diff_train = [x for x in train_columns if x not in test_columns]
diff_test = [y for y in test_columns if y not in train_columns]
x_train.drop(columns=diff_train)
x_test.drop(columns=diff_test)

test_columns[train_columns]
'''
