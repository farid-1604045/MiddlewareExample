This repository demonstrates how the ASP.NET Core request pipeline works. 
It includes examples of:

- Global middleware using `app.Use`
- Branching the pipeline with `app.Map`
- Conditional branching with `app.MapWhen`
- Terminal middleware using `app.Run`
- Integrating MVC controllers with `app.MapControllers`

The project can be tested using Postman or a browser to observe different middleware behaviors and logging order.
