<template>
    <Navbar expand="lg" background-color="white">
        <Container>
            <NavbarBrand href="/" aria-label="use bootstrap">
                <img src="~/assets/img/logo1.svg" height="30" alt="Logo" />
            </NavbarBrand>
            <NavbarToggler />
            <NavbarCollapse>
                <NavbarNavList margin="e-auto">
                    <NavItem>
                        <NavLink to="/docs" padding="x-0 x-lg-2">
                            移動場所
                        </NavLink>
                    </NavItem>
                </NavbarNavList>
            </NavbarCollapse>
        </Container>
    </Navbar>
</template>
