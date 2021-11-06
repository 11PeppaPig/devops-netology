# !!budut ignorirovatsa vse faili v kataloge '.terraform' dannogo repositoriya
#
# Local .terraform directories
**/.terraform/*

# !! budut ignorirovarsya vse faili s takim imenem i lyubim rashireniem 
#
# .tfstate files
*.tfstate
*.tfstate.*

# !! budut ignorirovatsya faili s takim imenem i rashireniem
#
# Crash log files
crash.log


# !! budut ignorirovatsya faili s dannim imenem v kotorom soderjetsya vajnaya informatsieya
#
# Exclude all .tfvars files, which are likely to contain sentitive data, such as
# password, private keys, and other secrets. These should not be part of version
# control as they are data points which are potentially sensitive and subject
# to change depending on the environment.
*.tfvars

#!!ignorirovat dannie faili poskolku oni ispolzuyutsya dlya perezapisi resursov v dannom repositorii
#
# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# !!faili kotorie nujno perezapisovat dobavit v spisok 'example_override.tf'
#
# Include override files you do wish to add to version control using negated pattern
#
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# !!ignorirovat dannie faili configuracii
#
# Ignore CLI configuration files
.terraformrc
terraform.rc

