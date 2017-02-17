# IdentityServer4
IdentityServer4 with Asp.NET CORE 1.1 VisualStudio 2017

Create ASP.NET Core Web Application(.NET CORE 1.1) with Individual User Accounts Authentication.

Add IdentityServer packages:
"IdentityServer4.AspNetIdentity",


PM> Add-Migration InitialIdentityServerMigration -c PersistedGrantDbContext -o Data/Migrations/PersistedGrants

PM> Add-Migration InitialIdentityServerMigration -c ConfigurationDbContext -o Data/Migrations/Configuration
