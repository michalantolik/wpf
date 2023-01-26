### 01 - WPF MVVM in Depth

**MVVM - Fundamental Equation**
- View.DataContext = ViewModel

**MVVM - Main Goal**
- Seperation of Concerns
  - Maintainability
  - Testability

**MVVM - Responsibilities**
- **Model**
  - Client-side data model
- **View-Model**
  - Data for the view + Interaction logic --> *presentation + manipulation*
- **View**
  - GUI for the user

**ViewModel Data**
- **Exposed model data** --> *model data classes used directly in ViewModel as properties*
- **Wrapped model data**
- **Client state** --> *e.g. LoggedIn*
