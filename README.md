- Clone the repo

```jsx
git clone https://github.com/100xdevs-cohort-2/week-17-final-code
```

- npm install
- Run postgres either locally or on the cloud (neon.tech)

```jsx
docker run  -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres
```

- Copy over all .env.example files to .env
- Update .env files everywhere with the right db url
- Go to `packages/db`
    - npx prisma migrate dev
    - npx prisma db seed
- Go to `apps/user-app` , run `npm run dev`
- Try logging in using phone - 1111111111 , password - alice (See `seed.ts`)

-  not add something just try.
-  not add something just try.
-  not add something just try.

- ssh -i c:\Users\pintu\Downloads\pintu-password.pem ubuntu@52.204.232.176

- ssh -i c:\Users\pintu\Downloads\pintu-password.pem ubuntu@ec2-52-204-232-176.compute-1.amazonaws.com

- echo "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC7fOk6bHXWsrHtyaJzytErvvrR+/y8C515DT+IXQDmLd1311eT1PkFFiF0t8LpPX7zDlBm+ZSYTKos3aT72Z7FlCfgaAuPbD/VI1smZ+3EWmDk/AyAhuKik9X74zuG2P0pXnQA5okf9wOGtQ1g3TSV6e6oM4kp7nvBgMIWl921GefjfHX8zFt+FXbDIJa0CTg/ZsB3wM2FW6CCRYJKLihDZ2PFepuvg6oHhVO2fzpOYaWzq+NxEvkO9aVj8zbVki7g0hGFuskQ4miHSP9qcpcqvVFi73T+mfJPy136gmiuWH9p2B19QFMNRPgmCc+Kwug16ZRavflvbhOBFp/fV/j9OgRMhqjJf8/qsT/kLTKg3wOnpYq8rGxUhZ5nSaez8MiPOkF75mK5hwuO/CUtw7anYRUPmTZ0bzQO2D5IxqCrHBOLPSWsZGcO1jxRiM3knkoDRtS3b0AWkhKCoSKz1PSsG9uFTAjgIY6TLiNQcqFY0uf+DmDjwMSl7/yMkWcxwnIXGf0A/siMEDsu3G9uBrpfYyPAGSmoqXXlLmIY5GVx246urVh/VM1zbp00aW46mPUQPiNLuUXxGn4TfBquvMfjnVSoOR6RfUjCAg4Ge4A/pVyEFy7so1zLZeo1LEQk/LIK/tp3GWWUwroi9/V7o1IxbdgbCUTb11G5oR5+5rqkgw== pintu1012kumar@gmail.com" >> ~/.ssh/authorized_keys