# project-108
#Weight In Poumds

from google.colab import files
data = files.upload()

import random
import plotly.express as px
import plotly.figure_factory as ff
import pandas as pd

df = pd.read_csv("data.csv")
fig = ff.create_distplot([df ["Weight(Pounds)"].tolist()], ["Weight"], show_hist=False )
fig.show()




#Height In Inches

from google.colab import files
data = files.upload()

import random
import plotly.express as px
import plotly.figure_factory as ff
import pandas as pd

df = pd.read_csv("data.csv")
fig = ff.create_distplot([df ["Height(Inches)"].tolist()], ["Height"], show_hist=False )
fig.show()
