SQL Commands -TESTI
--------------

SELECT *FROM avn;

ALTER TABLE public.avn ADD COLUMN tnum bigint default nextval(*ticket_sequence'::regclass) PRIMARY KEY;

ALTER TABLE avn ADD COLUMN status varchar(100);

CREATE TABLE public.avn(
  tnum bigint default nextval('ticket_sequence'::regclass),
  other_cloumn TEXT
);


INSERT INTO public.avn(product, pdesc, cont, date, status) VALUES('DIGITALTV', 'NW Issue'
INSERT INTO public.avn(pdesc) VALUES ('NOT WORKING') TRTURNING *;
INSERT INTO public.avn(cont) VALUES ('98734567384') TRTURNING *;
INSERT INTO public.avn(pdesc) VALUES ('NOT WORKING') TRTURNING *;
INSERT INTO public.avn(pdesc) VALUES ('NOT WORKING') TRTURNING *;
