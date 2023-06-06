# BD-P3-CASO-8
1*) π nome, ap, salario emp
2*) ρ Nombre ← nome, Apellido ← ap, Sueldo ← salario emp
3*) π nome, nom ((π nome,codd emp) ⨝ (π codd,nom dep))
4*) π nome (emp ⨝ (π codd σ nom= 'Finance' ∨ nom='Shipping' dep))
5*) π nomt σ salmin > 5000 trabajo
6*) (π code σ codd=90 historia) ∩ (π code σ codd=60 historia)
7*) AlexK=  ρ AlexK π salario σ code=115 emp
    π nome (AlexK ⨝ AlexK.salario = emp.salario ∧ emp.code ≠ 115 emp)
8*) SigalT=  ρ SigalT π salario σ code=117 emp
    π nome (SigalT ⨝ SigalT.salario < emp.salario ∧ emp.code ≠ 117 emp)
9*) A= π codt σ code=101 emp
    B= π codt σ code=101 historia
    π codt,nomt (trabajo ⨝ (A ∪ B))
10*)
11*) A= π codd dep
     π nomt (trabajo ⨝ (π codt,codd historia ÷ A))
12*) A= π localidad_id σ ciudad='Toronto' localidad
     B= π codd (dep ⨝ A)
     trabajo ⨝ (π codt,codd emp ÷ B)     
