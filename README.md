

<p align="center">
    <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/nvmelo/aspnet-web-app">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/nvmelo/aspnet-web-app?label=updated">
    <img alt="GitHub License" src="https://img.shields.io/github/license/nvmelo/aspnet-web-app">
    <a href="https://www.linkedin.com/in/nvmelo/">
        <img alt="Linkedin" src="https://img.shields.io/badge/LinkedIn-555.svg?logo=linkedin&style=flat"/>
    </a>
</p>




<br />

<p align="center">
  <a href="https://github.com/nvmelo/aspnet-web-app">
    <img src="https://www.flaticon.com/svg/static/icons/svg/718/718150.svg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">aspnet-web-app</h3>

  <p align="center">
    Web app using ASP.NET
  </p>
</p>

<!-- ERROR MESSAGES FOUND -->
## Error messages found

    CursoTest.CategoriasControllerTest.Get_Categoria
	    Fonte: CategoriasControllerTest.cs linha 33
	    Duração: 1 ms
	    
    Mensagem: 
	    System.NotSupportedException : Unsupported expression: m => m.Categorias
	    Non-overridable members (here: Context.get_Categorias) may not be used in setup / verification expressions.
    
    Rastreamento de Pilha: 
	    Guard.IsOverridable(MethodInfo method, Expression expression) linha 99
	    InvocationShape.ctor(LambdaExpression expression, MethodInfo method, IReadOnlyList`1 arguments, Boolean exactGenericTypeArguments, Boolean skipMatcherInitialization, Boolean allowNonOverridable) linha 82
	    ExpressionExtensions.<Split>g__Split|5_0(Expression e, Expression& r, InvocationShape& p, Boolean assignment, Boolean allowNonOverridableLastProperty) linha 304
	    ExpressionExtensions.Split(LambdaExpression expression, Boolean allowNonOverridableLastProperty) linha 148
	    Mock.SetupRecursive[TSetup](Mock mock, LambdaExpression expression, Func`4 setupLast, Boolean allowNonOverridableLastProperty) linha 618
	    Mock.Setup(Mock mock, LambdaExpression expression, Condition condition) linha 522
	    Mock`1.Setup[TResult](Expression`1 expression) linha 468
	    CategoriasControllerTest.ctor() linha 26

<!-- USED PACKAGES -->
## Used packages

 - coverlet.collector (v1.3.0)
 - Microsoft.AspNetCore.Authentication.JwtBearer (v5.0.1)
 - Microsoft.AspNetCore.Authentication.OpenIdConnect (v5.0.1)
 - Microsoft.EntityFrameworkCore.Sqlite (v5.0.1)
 - Microsoft.EntityFrameworkCore.SqlServer (v5.0.1)
 - Microsoft.EntityFrameworkCore.Tools (v5.0.1)
 - Microsoft.NET.Test.Sdk (v16.7.1)
 - Microsoft.VisualStudio.Web.CodeGeneration.Design (v5.0.1)
 - Moq (v4.15.2)
 - Swashbuckle.AspNetCore (v5.6.3)
 - xunit (v2.4.1)
 - xunit.runner.visualstudio (v2.4.3)

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Nereu Melo -  nereuvictor1@gmail.com

[Project link](https://github.com/nvmelo/aspnet-web-app)