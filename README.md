# Seguro para Emprendimientos

# Objetivo
El objetivo de este proyecto fue desarrollar un seguro que cubriese el capital inicial invertido de aquellos emprendimientos micro que recien inician operaciones en caso de que el negocio no tuviese éxito y por tanto, quedara en quiebra. Este plan se ofrece con una cobertura temporal de un año, diseñado exclusivamente para respaldar la seguridad financiera de los inversionistas en proyectos empresariales nuevos. 

# Metodología
* La información estadística utilizada para el cálculo de la siniestralidad corresponde a las tasas de cierre de los negocios por estado de la Demografía de los Negocios (DN) del INEGI.
* Se simuló una cartera de 20,000 negocios asegurados considerando el tamaño del negocio (micro o PyMe) y el estado de la república donde residía dicho negocio.
* Se utilizó VBA para simular 100 carteras diferentes de 20,000 negocios para calcular la frecuencia y severidad de las reclamaciones por tamaño de negocio y estado, con el objetivo de calcular la prima de riesgo.
* Se realizó un cotizador para calcular la prima de tarifa y la prima total considerando el tamaño de negocio y estado, gastos de administración, adquisición y utilidad, así como los derechos de póliza, IVA y recargo por pago fraccionado.
* Finalmente, se utilizaron las 100 carteras simuladas para calcular la Reserva de Riesgos en Curso (RRC) y la Reserva de Siniestros Ocurridos pero No Reportados (SONR) mediante el uso de triángulos de siniestralidad por el método Chain-Ladder.
