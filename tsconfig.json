import type { Config } from "tailwindcss";

const config: Config = {
    darkMode: ["class"],
    content: [
        "./pages/**/*.{js,ts,jsx,tsx,mdx}",
        "./components/**/*.{js,ts,jsx,tsx,mdx}",
        "./app/**/*.{js,ts,jsx,tsx,mdx}",
    ],
    theme: {
        extend: {
            colors: {
                /* Consulting Theme Colors */
                background: 'hsl(220, 20%, 98%)', // Soft professional white
                foreground: 'hsl(220, 15%, 10%)', // Deep navy (text)

                card: {
                    DEFAULT: 'hsl(220, 20%, 96%)', // Light grayish card background
                    foreground: 'hsl(220, 15%, 10%)',
                },

                popover: {
                    DEFAULT: 'hsl(220, 20%, 98%)',
                    foreground: 'hsl(220, 15%, 10%)',
                },

                primary: {
                    DEFAULT: 'hsl(220, 50%, 20%)', // Dark Consulting Blue
                    foreground: 'hsl(220, 20%, 98%)',
                },

                secondary: {
                    DEFAULT: 'hsl(220, 10%, 90%)', // Light Gray for contrast
                    foreground: 'hsl(220, 50%, 20%)',
                },

                muted: {
                    DEFAULT: 'hsl(220, 15%, 85%)',
                    foreground: 'hsl(220, 10%, 40%)',
                },

                accent: {
                    DEFAULT: 'hsl(220, 20%, 80%)', // Subtle blue-gray accents
                    foreground: 'hsl(220, 50%, 20%)',
                },

                destructive: {
                    DEFAULT: 'hsl(0, 80%, 50%)', // Consulting-style alert red
                    foreground: 'hsl(0, 0%, 98%)',
                },

                border: 'hsl(220, 15%, 75%)',
                input: 'hsl(220, 15%, 85%)',
                ring: 'hsl(220, 50%, 20%)',

                /* Consulting-Themed Chart Colors */
                chart: {
                    '1': 'hsl(210, 60%, 40%)', // BCG Green
                    '2': 'hsl(240, 50%, 50%)', // McKinsey Blue
                    '3': 'hsl(260, 40%, 35%)', // Dark Consulting Blue
                    '4': 'hsl(30, 75%, 60%)',  // Golden Accent
                    '5': 'hsl(350, 70%, 60%)', // Bain Red
                },
            },

            /* Refined Border Radius */
            borderRadius: {
                lg: '8px',
                md: '6px',
                sm: '4px',
            },

            /* Smooth Accordion Animations */
            keyframes: {
                'accordion-down': {
                    from: { height: '0' },
                    to: { height: 'var(--radix-accordion-content-height)' },
                },
                'accordion-up': {
                    from: { height: 'var(--radix-accordion-content-height)' },
                    to: { height: '0' },
                },
            },
            animation: {
                'accordion-down': 'accordion-down 0.2s ease-out',
                'accordion-up': 'accordion-up 0.2s ease-out',
            },

            /* Consulting-Themed Typography */
            fontFamily: {
                sans: ['Inter', 'Arial', 'sans-serif'], // Clean, professional font
            },

            fontSize: {
                base: '16px',
                lg: '18px',
                xl: '20px',
                '2xl': '24px',
                '3xl': '30px',
            },
        },
    },
    plugins: [require("tailwindcss-animate")],
};

export default config;
