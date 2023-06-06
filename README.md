# BD-P3-CASO-8
1*) π nome, ap, salario emp
2*) ρ Nombre ← nome, Apellido ← ap, Sueldo ← salario emp
3*) π nome, nom ((π nome,codd emp) ⨝ (π codd,nom dep))
4*) π nome (emp ⨝ (π codd σ nom= 'Finance' ∨ nom='Shipping' dep))
5*) π nomt σ salmin > 5000 trabajo
6*) (π code σ codd=90 historia) ∩ (π code σ codd=60 historia)
