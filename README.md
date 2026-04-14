# ML_project
“Simple Python ML project”
from sklearn.linear_model import LinearRegression

model = LinearRegression()
X = [[1], [2], [3]]
y = [2, 4, 6]

model.fit(X, y)
print(model.predict([[4]]))
