Tema abordată în cadrul proiectului este detectarea vaselor de sânge în imagini de fund de 
ochi, având ca scop facilitatea în diagnosticul unor boli oculare importante, cum ar fi 
retinopatia diabetică și glaucomul.   
Implementarea proiectului a fost făcută în Python, folosind biblioteci precum OpenCV, 
NumPy, Matplotlib pentru procesarea imaginilor. 
Utilizarea canalului verde pentru procesarea imaginii este justificată de sensibilitatea crescută 
în detectarea vaselor de sânge, iar algoritmi precum CLAHE și filtrul gaussian sunt 
implementați. S-au aplicat și operații morfologice, cum ar fi eroziunea și dilatarea pentru 
îmbunătățirea segmentării. Rezultatele obținute indică o îmbunătățire semnificativă a 
contrastului și o detectare clară a vaselor de sânge.  
Avantajele metodei includ simplitatea implementării și performanța sa pe imagini cu zgomot 
redus. Limitările constau în sensibilitatea la zgomotul ridicat și complexitatea vaselor de 
sânge, ceea ce poate afecta detecția precisă. 
Cuvinte cheie: detecție, vase de sânge, imagini fund de ochi 
Date de intrare: imagine color a fundului de ochi 
Date de ieșire: harta vaselor de sânge 
