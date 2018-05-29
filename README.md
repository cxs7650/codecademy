# codecademy

import codecademylib
#1
import numpy as np
#2
calorie_stats=np.genfromtxt('cereal.csv', delimiter=',')
print(calorie_stats)

#3
average_calories=np.mean(calorie_stats)
print(average_calories)

#4
calorie_stats_sorted=np.sort(calorie_stats)
print(calorie_stats_sorted)

#5
median_calories=np.median(calorie_stats)
print(median_calories)

#6
nth_percentile=np.percentile(calorie_stats, 3.5)
print(nth_percentile)

#7
more_calories=np.mean(calorie_stats > 60)
print(more_calories)

#8
calorie_std=np.std(calorie_stats)
print(calorie_std)
