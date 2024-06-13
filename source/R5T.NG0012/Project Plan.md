# R5T.NG0012
WinForms (Windows Forms) selector library.

Note that WinForms (System.Windows.Forms) cannot be selected as a NuGet package like all other functionality.

Instead, a project property <UseWindowsForms> must be set:

	<PropertyGroup>
		<TargetFramework>net6.0-windows</TargetFramework>
		<UseWindowsForms>true</UseWindowsForms>
	</PropertyGroup>
