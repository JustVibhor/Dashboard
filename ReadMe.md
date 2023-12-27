## Explaing the project

# Frontend

    Using Refine
        1. cra (Create React App)
        2. Rest Api
        3. Material UI
        4. Google Auth

    Blueprint

        pages
            login.tsx


        constants
            properties for some charts we using

        utils
            validate-form.ts
                checks if we have properly entered all the properties

        interfaces
            google
                to check what we have once the user logsIn

        components
            charts
                chart.config.ts
                    Properties for out charts

            layout
                sider
                    index.tsx
                        customize the sidebar

                header
                    index.tsx
                        customize the header

                title
                    index.tsx
                        customize the title (logo)
                            if collapsed just show logo
                            else show logo + name
