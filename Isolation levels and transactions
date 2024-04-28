-- Create a new transaction with a serializiable isolation level
START TRANSACTION ISOLATION LEVEL SERIALIZABLE;

-- Update records with a 50% reduction if greater than 100000
UPDATE ffiec_reci
SET RCON0352 = RCON0352 * 0.5
WHERE RCON0352 > 100000;

-- Commit the transaction
COMMIT;

-- Select a count of records still over 100000
SELECT COUNT(RCON0352)
FROM ffiec_reci
WHERE RCON0352 > 100000;
