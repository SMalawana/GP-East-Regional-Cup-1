# Regional Cup GP East

Secure production version of the Regional Cup GP East tournament dashboard.

## Features

- Public fixture viewing
- Public standings and bracket viewing
- Public match dispute submission
- Supabase Auth admin login
- Admin-only scoring and fixture updates
- Supabase RLS protection

## Security Notes

- Public users can view tournament state.
- Public users can submit disputes only.
- Admin users must log in with Supabase Auth.
- No service-role keys are stored in the frontend.