# World Visa Express — Full Website

### Features
- Visa Services, Apply, Requirements, Status Check
- Automatic Application ID generation
- Admin Panel
- Admin can change status: Pending / Processing / Approved / Rejected
- Public users can check status by Application ID

### Run
Node.js 18+ required.
1. `npm install`
2. `npm start`
3. Open `http://localhost:3000`
4. Admin: `http://localhost:3000/admin.html`

Default admin (change before live deployment):
- Username: `Admin`
- Password: `ShamimRm@777`

For production, use HTTPS, a real database, and environment variables ADMIN_USER, ADMIN_PASS and SESSION_SECRET.
