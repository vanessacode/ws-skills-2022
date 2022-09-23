# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE ✔️
Spécifie les erreurs dans le terminal

- les types de bases ✔️
Number, String, Boolean, Void

- comment et pourquoi étendre une interface ✔️
Les interfaces permettent au JavaScript de connaître la version typée des objets qui doivent être utilisés.

- les classes et les decorators ✔️
Un "Decorator" est un type spécial de déclaration qui peut être appliqué à des classes, des méthodes...
Ce sont des fonctions préfixées par @decorator

## 💻 J'utilise

### Un exemple personnel commenté ✔️
```
@Entity()
export class Wilder {
  @PrimaryGeneratedColumn()
  id: number;

  @Column()
  name: string;

  @Column()
  description: string;

  @OneToMany(() => Grade, (grade) => grade.wilder)
  grade: Grade[];
}
```

### Utilisation dans un projet ✔️

### Utilisation en production si applicable❌

### Utilisation en environement professionnel ❌

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
