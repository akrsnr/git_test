ALTER TABLE batutacardb.serviceaccount ADD IsAddToStock TINYINT DEFAULT 1 NOT NULL;

ALTER TABLE batutacardb.serviceaccount DROP COLUMN InvoiceDate;
ALTER TABLE batutacardb.serviceaccount DROP COLUMN InvoiceCount;
