UPDATE `universities` AS u
SET `tuition_fee` = `tuition_fee` + 300
WHERE u.`id` BETWEEN 5 AND 12;