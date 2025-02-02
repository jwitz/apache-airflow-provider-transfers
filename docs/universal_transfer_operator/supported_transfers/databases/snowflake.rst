*********
Snowflake
*********

Transfer to Snowflake as destination dataset
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
User can transfer data to Snowflake as destination as from following sources dataset:

#. :ref:`table`

    .. literalinclude:: ../../../../src/universal_transfer_operator/constants.py
       :language: python
       :start-after: [START database]
       :end-before: [END database]

#. :ref:`file`

    .. literalinclude:: ../../../../src/universal_transfer_operator/constants.py
       :language: python
       :start-after: [START filelocation]
       :end-before: [END filelocation]

Following transfer modes are supported:

1. :ref:`non_native`
    Following is an example of non-native transfers between AWS S3 to Snowflake using non-native transfer:

    .. literalinclude:: ../../../../example_dags/example_universal_transfer_operator.py
       :language: python
       :start-after: [START transfer_non_native_s3_to_snowflake]
       :end-before: [END transfer_non_native_s3_to_snowflake]

2. :ref:`third_party`

Examples
########
1. AWS S3 to Snowflake transfers
    - :ref:`non_native`
        Following is an example of non-native transfers between AWS S3 to Snowflake using non-native transfer:

            .. literalinclude:: ../../../../example_dags/example_universal_transfer_operator.py
               :language: python
               :start-after: [START transfer_non_native_s3_to_snowflake]
               :end-before: [END transfer_non_native_s3_to_snowflake]

    - :ref:`third_party`
        Following is an example of transfers between AWS S3 to Snowflake using Fivetran with connector passed:

            .. literalinclude:: ../../../../example_dags/example_dag_fivetran.py
               :language: python
               :start-after: [START fivetran_transfer_with_setup]
               :end-before: [END fivetran_transfer_with_setup]

        Following is an example of transfers between AWS S3 to Snowflake using Fivetran without connector passed:

            .. literalinclude:: ../../../../example_dags/example_dag_fivetran.py
               :language: python
               :start-after: [START fivetran_transfer_without_setup]
               :end-before: [END fivetran_transfer_without_setup]

2. GCS to Snowflake transfers
    - :ref:`non_native`
        Following is an example of non-native transfers between GCS to Snowflake using non-native transfer:

            .. literalinclude:: ../../../../example_dags/example_universal_transfer_operator.py
               :language: python
               :start-after: [START transfer_non_native_gs_to_snowflake]
               :end-before: [END transfer_non_native_gs_to_snowflake]

2. Bigquery to Snowflake transfers
    - :ref:`non_native`
        Following is an example of non-native transfers between Bigquery to Snowflake using non-native transfer:

            .. literalinclude:: ../../../../example_dags/example_universal_transfer_operator.py
               :language: python
               :start-after: [START transfer_non_native_bigquery_to_snowflake]
               :end-before: [END transfer_non_native_bigquery_to_snowflake]


Transfer from Snowflake as source dataset
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
User can transfer data from Snowflake to the following destination dataset:

#. :ref:`table`

    .. literalinclude:: ../../../../src/universal_transfer_operator/constants.py
       :language: python
       :start-after: [START database]
       :end-before: [END database]

#. :ref:`file`

    .. literalinclude:: ../../../../src/universal_transfer_operator/constants.py
       :language: python
       :start-after: [START filelocation]
       :end-before: [END filelocation]

Following transfer modes are supported:

1. :ref:`non_native`
