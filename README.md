import numpy as np
import matplotlib.pyplot as plt

def plot_cosine_wave():
    x = np.arange(0, 361, 1)  # Values from 0 to 360 degrees
    y = np.cos(np.radians(x))  # Calculate cosine values
    
    plt.plot(x, y)
    plt.xlabel('Degrees')
    plt.ylabel('cos(x)')
    plt.title('Cosine Wave')
    plt.grid(True)
    plt.show()

plot_cosine_wave()

