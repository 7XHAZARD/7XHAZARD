
import pandas as pd
 import numpy as np
 dict = {'First Score':[100, 90, np.nan, 95],
        'Second Score': [30, 45, 56, np.nan],
        'Third Score':[np.nan, 40, 80, 98]}
 df = pd.DataFrame(dict)
 df.isnull()

import pandas as pd
data = pd.read_csv("employees.csv")
 bool_series = pd.isnull(data["Gender"])
 data[bool_series]

import pandas as pd
import numpy as np
 dict = {'First Score':[100, 90, np.nan, 95],
        'Second Score': [30, 45, 56, np.nan],
        'Third Score':[np.nan, 40, 80, 98]}
df = pd.DataFrame(dict)
 df.notnull()

import pandas as pd
data = pd.read_csv("employees.csv")
bool_series = pd.notnull(data["Gender"])
data[bool_series]

import pandas as pd
 import numpy as np
 dict = {'First Score':[100, 90, np.nan, 95],
        'Second Score': [30, 45, 56, np.nan],
        'Third Score':[np.nan, 40, 80, 98]}
 df = pd.DataFrame(dict)
df.fillna(0)
