-- Create a new transaction with an isolation level of repeatable read
START TRANSACTION ISOLATION LEVEL REPEATABLE READ;

-- Count of records over 100000000
SELECT COUNT(RCON2210)
FROM ffiec_reci
WHERE RCON2210 > 100000000;

-- Count of records over 100000000
SELECT COUNT(RCON2210)
FROM ffiec_reci
WHERE RCON2210 > 100000000;

-- Commit the transaction
COMMIT;
