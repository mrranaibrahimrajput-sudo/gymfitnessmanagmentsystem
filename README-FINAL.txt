GYMCORE - FINAL GYM FITNESS MANAGEMENT SYSTEM

Technology: ASP.NET Core MVC / .NET 8 / SQLite / Entity Framework Core

FEATURES
- Dashboard statistics
- Member registration and automatic Member ID
- Member search and status filters
- Member profile, edit and delete
- Membership plans: Monthly, Quarterly, Six Months, Yearly
- Automatic membership expiry calculation
- Membership renewal
- Payment records and revenue
- Weight progress history
- Current weight auto-update when progress is recorded
- Daily attendance
- Diet plan and notes
- Trainer assignment
- Responsive UI

FIRST RUN ON AN EXISTING COPY
1. Open GymFitnessManagementSystem.sln in Visual Studio 2022.
2. Make sure the solution is restored/built.
3. The included gymfitness.db already contains the existing member and the new tables.
4. Press Ctrl+F5 or click the HTTPS Run button.

IF YOU WANT TO RECREATE THE DATABASE
- Back up gymfitness.db first.
- Delete gymfitness.db.
- Open Package Manager Console.
- Run: Update-Database

The project contains the original InitialCreate migration plus AddGymFeatures.
