# prueba_AB
Esta investigación tiene como propósito comprobar si dentro de los 14 días posteriores a la inscripción, los usuarios mostrarán una mejor conversión en vistas de la página del producto, instancias de agregar artículos en el carrito de compras y compras con 6000 participantes de la prueba.
## Data:
**El dataset participants contiene los siguientes campos:**

- *user_id* — id del usuario.
- *ab_test* — nombre de la prueba.        
- *group*  — el grupo de prueba al que pertenecía el usuario.

**El dataset events contiene los siguientes campos:**

- *user_id* — id del usuario
- *event_dt* — fecha y hora del evento.        
- *event_name*  —  nombre del tipo de evento.  
- *details* — datos adicionales sobre el evento (por ejemplo, el pedido total en USD para los eventos purchase).

**El dataset users contiene los siguientes campos:**

- *user_id* — id del usuario 
- *first_date* — fecha de inscripción        
- *region*  — región a la que pertenece 
- *device*  — dispositivo utilizado para la inscripción

**El dataset events_marketing contiene los siguientes campos:**

- *name* — el nombre del evento de marketing 
- *regions* — regiones donde se llevará a cabo la campaña publicitaria         
- *start_dt* — fecha de inicio de la campaña      
- *finish_dt*  — fecha de finalización de la campaña


## Libraries used:

pandas

matplotlib.pyplot

plotly 

plotly.express 

seaborn

numpy

math

scipy import stats as st



