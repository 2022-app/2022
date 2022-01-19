# 2022

2022 est un test de positionnement pour l'élection présidentielle de 2022.

## Développement

```
npm ci
npm run dev
```

## Score

- Pour une réponse <img src="https://render.githubusercontent.com/render/math?math=r_i"> à une proposition (de très défavorable à très favorable, -2 à 2),
et une réponse du candidat <img src="https://render.githubusercontent.com/render/math?math=r'_i"> (contre, sans avis ou pour, -1 à 1), on gagne <img src="https://render.githubusercontent.com/render/math?math=p_i = r_i * r'_i"> points. Le score des réponses face au candidat est la somme des <img src="https://render.githubusercontent.com/render/math?math=p_i">, normalisée face à la somme des valeurs absolues des points <img src="https://render.githubusercontent.com/render/math?math=p_i">, et exprimée sous forme de pourcentage.
- On a <img src="https://render.githubusercontent.com/render/math?math=\delta_i = 0"> si le candidat ou l'utilisateur ne répond pas à la proposition <img src="https://render.githubusercontent.com/render/math?math=i">, <img src="https://render.githubusercontent.com/render/math?math=1"> sinon. La représentativité des réponses face au candidat est la somme des <img src="https://render.githubusercontent.com/render/math?math=\delta_i">, exprimée sous forme de pourcentage.


