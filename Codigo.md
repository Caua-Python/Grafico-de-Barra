import matplotlib.pyplot as plt

import numpy as np

aplicativos = ['Youtube', 'Safari', 'WhatsApp', 'LinkedIn']

horas_usadas = [29, 13, 5, 3]       

cores = ['red', 'royalblue',  '#25D366', '#0077B5']

plt.bar(aplicativos, horas_usadas,  color=cores)

plt.title("Aplicativos vs Horas usadas", fontweight='bold', fontsize=20)
plt.xlabel("Aplicativos", fontweight='bold', fontsize=15)
plt.ylabel("Horas Usadas", fontweight='bold', fontsize=15)

plt.gca().spines[['top', 'right']].set_visible(False)

plt.tight_layout()

plt.show()
